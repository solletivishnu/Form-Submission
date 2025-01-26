# Form Validation And Submission

## Overview
I recently worked on a Form Validation and Submission Application that dynamically validates user inputs and submits the data to an API endpoint. This project focuses on ensuring user-friendly interactions with robust error handling while leveraging modern JavaScript techniques.

## Features
### Dynamic Validation:
- Validates name and email fields in real-time, displaying error messages for missing or incorrect inputs.
### Gender Selection:
- Allows users to choose their gender (Male/Female) via radio buttons.
### Status Selection: 
- Enables users to select their working status from a dropdown.
### API Integration: 
- Submits user data to the GoRest API using the fetch method with a POST request.
### Error Handling: 
- Displays a custom error message if the email already exists in the system (e.g., "Email Already Exists").
### Clean User Experience: 
- Prevents form submission until all required fields are filled out correctly.


## Technologies Used
- **Frontend:**
- HTML: For structuring the form elements.
- CSS: For styling the form and error messages (optional if integrated).
- JavaScript:
    - DOM Manipulation for dynamic validation and UI updates.
    - Fetch API for sending data to the server.
 
## How It Works:

## Form Data Handling:
- The formData object stores the values for name, email, status, and gender.
- Each input field (name, email, etc.) updates the formData dynamically through change events.

## Validation:
- On form submission, validateFormData checks if required fields are empty and displays error messages.
## API Integration:
- The submitFormData function sends the formData to the GoRest API using a POST request.
- If the email already exists, the app displays an appropriate error message (Email Already Exists).
## Prevent Default Submission:
The submit event is intercepted using event.preventDefault() to ensure the form doesn't refresh the page.



# Screenshot of the Project
![Image](https://github.com/user-attachments/assets/72a6df59-4d26-48ab-aeec-77fcd019adff)

# After Form submission
![Image](https://github.com/user-attachments/assets/ea55c3d3-363c-4cb3-90ae-9b6dd7f20ed7)
