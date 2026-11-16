# Developer Portfolio

A responsive, single-page portfolio website template for a full-stack web developer. It is built with HTML, CSS, and vanilla JavaScript, with no build step or package installation required.

## Features

- Responsive layout with mobile navigation
- Dark and light themes, with the selected theme saved in the browser
- About, resume, skills, projects, and contact sections
- Project detail modals
- Active navigation state while scrolling
- Demo contact form with an on-page status message

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a browser.

To run it through XAMPP, place the project folder in `htdocs` and visit `http://localhost/personal_developer_portfolio/`.

## Customize

Edit `index.html` to update the profile, resume, skills, project cards, contact details, and social links. Replace the sample photo and project images with your own, and update the project data in the page's script so the detail modals match the cards.

The resume buttons link to `resume.pdf`; add your resume at the project root or change those links. Update the example email and social URLs before publishing.

`styles.css` contains the portfolio's styles, including responsive layouts and theme colors. Tailwind CSS, Google Fonts, and Font Awesome are loaded from CDNs, so those resources require an internet connection.

## Notes

- The contact form is front-end only and does not send or store messages. Connect it to a backend or form service to enable submissions.
- Project links and profile content are examples; replace them with your real information.
