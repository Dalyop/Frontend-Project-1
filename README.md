# Personal Portfolio Website

A modern, responsive portfolio website built with **HTML**, **CSS**, and **JavaScript**.

## Features

- 🖼️ Project showcase with interactive cards
- 🎨 Smooth animations and transitions
- 📱 Fully responsive design for all devices
- 🚀 Modern layout with a stylish carousel at the top
- ✉️ Contact form integration with email services

## Contact Form Requirement

To add a contact form that submits to your email, you must use one of the following email services. Each service allows you to collect form submissions without building a backend:

| Service         | Frontend-Only? | Free Plan | Best For                  |
|-----------------|:--------------:|:---------:|--------------------------|
| **Formspree**   | ✅             | Yes       | Simple HTML projects      |
| **EmailJS**     | ✅             | Yes       | React/JS-based forms      |
| **Formsubmit**  | ✅             | Yes       | Simplicity               |
| **Netlify Forms** | ✅ (Netlify) | Yes       | Netlify-hosted sites      |
| **Nodemailer**  | ❌             | N/A       | Custom backend needs      |

### How to Integrate

- **Formspree**: Add their form action URL to your `<form>` tag. No backend required.
- **EmailJS**: Use their JavaScript SDK to send emails directly from your frontend.
- **Formsubmit**: Set your form's action to their endpoint. No backend required.
- **Netlify Forms**: Add a special attribute to your form and deploy on Netlify.
- **Nodemailer**: Requires a custom backend (Node.js). Not recommended for frontend-only projects.

> **Tip:** Choose a service that matches your hosting and technical needs. For most students, Formspree or Formsubmit is the easiest.

## Getting Started

1. Clone or download this repository.
2. Open `public/index.html` in your browser to view the site.
3. Edit the files in the `assets` folder to add your own content and functionality.

## Structure

- `public/index.html` – Main HTML file
- `assets/style.css` – Styles for layout, carousel, and cards
- `assets/script.js` – JavaScript for interactivity

---