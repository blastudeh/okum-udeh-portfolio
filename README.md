# Okum Udeh — cybersecurity portfolio design

A static portfolio website design focused on system administration and cybersecurity. It contains a single HTML page with embedded CSS and JavaScript.

## Contents

- [Portfolio source](portfolio/index.html.html): page structure, styling and browser interactions.
- Sections for an introduction, background, portfolio cards, skills, articles, education, services and contact.
- Mobile navigation and smooth scrolling.

## Preview on Ubuntu

Open `portfolio/index.html.html` directly in your browser, or run this command from the repository root:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit `http://127.0.0.1:8000/portfolio/index.html.html`. Stop with Ctrl+C. The existing filename has two HTML extensions, so use the full path above.

## Important behavior

The contact form is a demonstration: JavaScript displays an alert and clears the form. It does **not** send email or save messages. Some cards and social/article links use placeholder destinations. Page descriptions are portfolio copy, not evidence that the linked projects or certifications were independently verified.

## Maintenance

Edit the HTML file to update text, styles and links. Check navigation, mobile sizing and all destinations after changes. No package installation or compilation is needed for the static page. A live deployment was not verified during this documentation review.

