# User Registration Form

This repository contains a simple, responsive user registration form built with HTML, Tailwind CSS, and vanilla JavaScript. It includes client-side validation for a smooth user experience and demonstrates form submission using Getform.io.

-----

## Features

  * **Responsive Design**: Adapts to various screen sizes using Tailwind CSS.
  * **Client-Side Validation**:
      * **Real-time feedback** for required fields, email format, password strength, and matching passwords.
      * **Password Strength Indicator**: Visually guides users to create strong passwords.
      * **Birthdate validation**: Ensures the date is not in the future.
      * **Phone number validation** with separate country code and number fields.
  * **Password Visibility Toggle**: Allows users to show/hide their password for easier input.
  * **Submission Handling**: Simulates form submission to Getform.io with loading states and success messages.
  * **Error and Success Messages**: Provides clear feedback to the user on validation errors and successful registration.

-----

## Technologies Used

  * **HTML5**: Structure of the web page.
  * **Tailwind CSS**: Utility-first CSS framework for rapid UI development and responsive design.
  * **Font Awesome**: Icons used in the form fields.
  * **Vanilla JavaScript**: For all client-side validation, form submission logic, and UI interactions.
  * **Getform.io**: (Used as a backend for demonstration) A service to handle form submissions without writing server-side code.

-----

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

You only need a web browser to view this form. No special server setup is required since it's a static HTML file with client-side JavaScript.

### Installation

1.  **Clone the repository (or download the file):**
    If you're using Git, you can clone the repository:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

    Alternatively, you can simply download the `index.html` (or whatever you name it) file containing the provided code.

2.  **Open the file in your browser:**
    Navigate to the directory where you saved the HTML file and open it with your preferred web browser. For example, double-click `index.html`.

-----

## Usage

Fill out the form fields. The form will provide real-time feedback on input validity.

  * **Username**: Must be at least 3 characters.
  * **Email Address**: Must be a valid email format.
  * **Password**: Must be at least 8 characters and include at least one uppercase letter, one lowercase letter, one number, and one special character. The password strength bar will update as you type.
  * **Confirm Password**: Must match the password field.
  * **Birthdate**: Cannot be a future date.
  * **Full Address**: Required field.
  * **Phone Number**: Requires a country code (1-4 digits) and a phone number (7-15 digits).

Upon successful validation, clicking the "**Register**" button will simulate a submission to `https://getform.io/f/awnwymzb`. A success message will appear, and the form will reset.

-----

## Form Submission (Getform.io)

This form is configured to submit data to a [Getform.io](https://getform.io/) endpoint. This is a convenient way to test form submissions without setting up a backend server.

**Note**: The provided `action` URL (`https://getform.io/f/awnwymzb`) is a generic one for demonstration. If you intend to use Getform.io for your own project, you'll need to create your own form endpoint on their platform and update the `action` attribute in the `<form>` tag.

-----

## Customization

  * **Styling**: Modify the `<style>` block in the `<head>` section or add external CSS files to change the appearance. You can also adjust Tailwind CSS classes directly in the HTML.
  * **Validation Rules**: All validation logic resides within the `<script>` tag at the end of the `<body>`. You can adjust the validation rules (e.g., password complexity, phone number regex) by modifying the JavaScript functions.
  * **Form Endpoint**: Change the `action` attribute of the `<form>` tag to your desired submission endpoint if you're not using Getform.io or want to use a different Getform.io endpoint.

-----

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests.

-----

## License

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).
