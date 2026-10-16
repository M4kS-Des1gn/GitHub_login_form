# GitHub Login & Registration Page

A responsive website that recreates the appearance of GitHub's login and registration pages using HTML, CSS, and JavaScript. The project demonstrates form design, input validation, basic authentication logic, and user feedback.

## Features

### Login Page (`login.html`)
- Username or email and password input fields.
- Required-field validation.
- Basic login verification using JavaScript.
- Success and error messages displayed with SweetAlert2.
- Links to the registration page and a placeholder for password recovery.
- Buttons for Google and Apple sign-in (visual demonstration only).

### Registration Page (`register.html`)
- Email, password, username, and country selection fields.
- Password validation:
  - At least 15 characters, or
  - At least 8 characters, including a number and a lowercase letter.
- Username validation allowing letters, numbers, and single hyphens between alphanumeric groups.
- Optional email notifications checkbox.
- Success message and redirection to the login page.
- Responsive two-column layout with custom CSS illustrations.
- Navigation between login and registration pages.

### Design
- Dark GitHub-inspired login page.
- Light registration form with a dark introductory section.
- Shared CSS stylesheet for consistent styling.
- Responsive layout for desktop, tablet, and mobile screens.
- Hover effects, focus indicators, and styled form controls.

## Technologies Used

- **HTML5** – Page structure and forms.
- **CSS3** – Styling, layouts, gradients, illustrations, and responsive design.
- **JavaScript** – Form handling, input validation, and page navigation.
- **SweetAlert2** – User-friendly popup notifications.
- **GitHub** – Version control and repository hosting.

## Project Structure

```text
project/
├── login.html
├── register.html
├── CSS/
│   └── style.css
└── images/
    ├── httpsuxwing.comgithub-icon.png
    └── apple.png
```

The `images/` folder contains the logo and icons used on the pages. The `CSS/style.css` file contains the shared styles for both pages.

## How to Run the Project

1. Download or clone the repository.
2. Make sure the `CSS` and `images` folders are in the correct locations.
3. Open `login.html` in a web browser.
4. Click **Ustvari račun** (Create account) to open the registration page.
5. Use the form to test the validation and navigation features.

An internet connection is required to load the SweetAlert2 library from its CDN.

## Test Login Credentials

The login page uses hardcoded credentials for demonstration purposes.

| Field | Value |
|---|---|
| Username | `student` |
| Password | `Pass1234!` |

Enter these credentials to display the successful login message. Any other combination displays an error message.

## Important Limitations

This project is a front-end demonstration and is **not a functional authentication system**.

- User accounts are not stored in a database.
- Login credentials are hardcoded in JavaScript.
- Registration does not create a real account.
- Google and Apple sign-in buttons are visual elements only.
- Password recovery is not implemented.
- Authentication and password security are not provided.

For a production application, authentication should be implemented using a secure backend, a database, password hashing, and appropriate session management.

## Purpose of the Project

The purpose of this project is to practise web development fundamentals, including HTML forms, CSS styling, responsive layouts, JavaScript event handling, form validation, and navigation between web pages.

---

**Project type:** Front-end web development  
**Languages:** HTML, CSS, JavaScript  
**Status:** Educational demonstration
