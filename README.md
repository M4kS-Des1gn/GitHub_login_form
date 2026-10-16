# GitHub Login & Registration Demo

A responsive front-end website inspired by GitHub's login and registration pages. The project includes a demonstration notice, a login page, and a registration page, using HTML, CSS, and JavaScript.

**Note:** This is an unofficial educational project and is not affiliated with GitHub.

## Features

### 1. Demo Notice (`index.html`)
- Displays a notice explaining that the website is an unofficial copy.
- Includes the GitHub logo and a custom-styled information card.
- Provides navigation links to the login and registration pages.
- Uses a highlighted notice label and accessible navigation.

<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/b08ac7d1-eda9-49e4-9038-704c2d3593df" />



### 2. Login Page (`login.html`)
- Username or email and password fields.
- Required-field validation.
- Basic login verification using JavaScript.
- Success and error notifications using SweetAlert2.
- Links to the registration page and a placeholder for password recovery.
- Google and Apple sign-in buttons for visual demonstration.

**Test credentials:**
- Username: `student`
- Password: `Pass1234!`

<img width="1920" height="949" alt="image" src="https://github.com/user-attachments/assets/d8317246-2064-4eb3-a747-5171d09ebf00" />


### 3. Registration Page (`register.html`)
- Email, password, username, and country selection fields.
- Password validation based on length and character requirements.
- Username validation allowing letters, numbers, and single hyphens between alphanumeric groups.
- Optional product update emails.
- Success notification and redirection to the login page.
- GitHub-inspired benefits section with custom CSS illustrations.
- Link back to the login page.

<img width="1920" height="950" alt="image" src="https://github.com/user-attachments/assets/8563117c-dde6-4927-af88-10fda923c142" />


### 4. Design and Responsiveness
- GitHub-inspired dark and light themes.
- Shared CSS stylesheet for consistent styling.
- Responsive registration layout for desktop, tablet, and mobile devices.
- Custom gradients, illustrations, hover effects, and focus indicators.
- Styled buttons, forms, and notification cards.

## Technologies Used

- **HTML5** – Website structure and forms.
- **CSS3** – Layouts, colors, responsive design, gradients, and illustrations.
- **JavaScript** – Form validation, event handling, and page navigation.
- **SweetAlert2** – Popup notifications.
- **GitHub** – Version control and repository hosting.
- **GitHub Pages** – Optional static website hosting.

## Project Structure

```text
project/
├── index.html
├── login.html
├── register.html
├── CSS/
│   └── style.css
└── images/
    ├── httpsuxwing.comgithub-icon.png
    └── apple.png
```

- `index.html` – Landing page with the demo notice.
- `login.html` – Login form and basic credential verification.
- `register.html` – Registration form and input validation.
- `CSS/style.css` – Shared styling for all pages.
- `images/` – Logos and icons used throughout the website.

## How to Run the Project

1. Clone or download the repository.
2. Make sure all files and folders retain their original structure.
3. Open `index.html` in a web browser.
4. Select **Continue to login** or **Go to registration**.
5. Test the login and registration forms.

An internet connection is required to load SweetAlert2 from its CDN and the external Google icon used on the login page.

## Limitations

This project is intended for educational and demonstration purposes only.

- Login credentials are hardcoded in JavaScript.
- Registration does not create or store real user accounts.
- Google and Apple authentication are not implemented.
- Password recovery is not functional.
- No database or backend server is connected.
- Form validation does not provide real account security.

A production-ready application would require a secure backend, database integration, password hashing, and proper authentication and session management.

## Purpose

The purpose of this project is to practise HTML, CSS, and JavaScript by recreating common authentication interfaces. It demonstrates form creation, client-side validation, responsive design, page navigation, and user notifications.

---

**Project type:** Front-end web development  
**Languages:** HTML, CSS, JavaScript  
**Status:** Educational demonstration  
**Affiliation:** Unofficial project, not affiliated with GitHub
