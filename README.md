# GitHub Login and Registration Interface

## Description

This project is a simple website that recreates the appearance of GitHub's login and registration pages. It is developed using HTML, CSS, and JavaScript.

The website allows users to switch between login and registration forms, enter their account information, and receive feedback through alert messages. The design uses a dark theme inspired by GitHub's interface.

**Note:** This is an educational demonstration project and is not an official GitHub application.

## Features

### Login Page (`index.html`)

* Enter a username or email address.
* Enter a password.
* Validate login credentials using predefined demo credentials.
* Switch between login and registration modes.
* Display success or error messages.
* Display Google and Apple login buttons as visual elements.
* Include a forgotten-password link.

### Registration Page (`register.html`)

* Enter a username with a minimum length of 3 characters.
* Enter an email address.
* Create a password with a minimum length of 8 characters.
* Confirm the password.
* Check whether both passwords match.
* Display a registration confirmation message.
* Redirect the user to the login page after successful registration.

### Design and Styling

* Dark theme inspired by GitHub.
* Responsive layout for different screen sizes.
* Centered authentication forms.
* Styled input fields, buttons, and links.
* Hover and focus effects for interactive elements.
* GitHub, Google, and Apple logos.

## Technologies Used

* **HTML5** – Website structure and form elements.
* **CSS3** – Layout, colors, typography, and interactive styling.
* **JavaScript** – Form handling, basic validation, and navigation.

No backend or database is currently used.

## Project Structure

```text
GitHub-Login/
├── index.html
├── register.html
├── CSS/
│   └── style.css
├── images/
│   ├── httpsuxwing.comgithub-icon.png
│   └── apple.png
└── README.md
```

## How to Run

1. Download or clone the project.
2. Make sure the HTML, CSS, and image files are in the correct directories.
3. Open `index.html` in a web browser.
4. Use the login form or select **Ustvari račun** to switch to registration.
5. Alternatively, open `register.html` directly to access the registration page.

No server or additional installation is required for the current demonstration.

## Demo Login Credentials

The login page uses predefined credentials stored in its JavaScript code.

| Field    | Value       |
| -------- | ----------- |
| Username | `student`   |
| Password | `Pass1234!` |

Enter these credentials on the login page to display a successful login message.

## How It Works

### Login

The JavaScript code prevents the default form submission and checks the entered username and password against the predefined demo credentials. A success or error alert is displayed depending on the result.

### Registration

The registration form checks whether the password and confirmation match. If they match, a success message appears and the browser redirects to `index.html`.

The login page also contains a registration mode that can be enabled without navigating to another page.

### Styling

The `style.css` file defines the layout, dark background, input fields, buttons, links, and responsive form width. It is shared by both HTML pages to maintain a consistent appearance.

## Limitations

* User accounts are not saved.
* Registration does not create a real account.
* Login credentials are hardcoded in JavaScript.
* Google and Apple login buttons do not perform authentication.
* The forgotten-password link does not reset a password.
* Password strength is not checked.
* The login and registration forms do not communicate with a server or database.

## Future Improvements

* Add a backend using PHP, Java, Node.js, or another server-side technology.
* Store user accounts securely in a database.
* Implement password hashing and secure authentication.
* Add functional Google and Apple authentication.
* Implement password recovery.
* Improve validation and error messages.
* Add accessibility improvements and automated tests.

## Security Notice

This project is intended for educational purposes only. The predefined login credentials and client-side validation are not secure enough for a real authentication system. Never use this implementation to protect real accounts or sensitive information.

## Author

Created as a learning project to practice HTML, CSS, JavaScript, form validation, and basic web authentication interface design.
