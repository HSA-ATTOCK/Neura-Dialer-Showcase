# Neura Dialer Showcase

A static showcase for a professional Twilio-powered dialer solution. This repository contains a single-page HTML/CSS/JavaScript demo of the dialer UI, screenshots gallery, feature descriptions, pricing mockups, and a contact modal. It's a converted version of a React component into a standalone static site.

## Contents

- `TwilioDialerShowcase.html` - The main HTML file with all markup and client-side JS for interactivity (tabs, modal, image viewer).
- `TwilioDialerShowcase.css` - Styles for the showcase.
- Images (e.g. `login.png`, `dialer.png`, `adminpanel.png`, etc.) used in the screenshots gallery.

## Features

- Hero section with CTAs
- Sticky navigation tabs (Overview, Features, Screenshots, Technology)
- Screenshots gallery with full-size image modal viewer
- Contact form modal with plan selection and form validation
- Smooth scrolling and tab switching
- Responsive layout and print-friendly styles

## Tech Stack

- HTML5
- CSS3 (modern layouts, gradients)
- Vanilla JavaScript (no frameworks)

## How to run locally

1. Clone the repository:

```powershell
git clone https://github.com/HSA-ATTOCK/Neura-Dialer-Showcase.git
cd Neura-Dialer-Showcase
```

2. Open the HTML file in your browser:

```powershell
# Windows
start TwilioDialerShowcase.html

# macOS
open TwilioDialerShowcase.html

# Or, serve via a simple HTTP server while developing:
python -m http.server 8000
# then open http://localhost:8000/TwilioDialerShowcase.html
```

Notes: For correct relative image loading, keep the HTML and images together in the same folder.

## Deployment

This is a static site and can be hosted on any static file host (GitHub Pages, Netlify, Vercel, S3 + CloudFront). For GitHub Pages:

1. In the repository settings, enable GitHub Pages and set the source to the `main` branch.
2. Alternatively, build a small workflow to deploy from `main`.

## Editing & Extending

- To add more screenshots, place your image files in the repository and add another `.screenshot-card` block in `TwilioDialerShowcase.html` (see existing cards for structure).
- To change contact behavior (send emails, integrate with backend), replace the `contactForm.onsubmit` handler in the `<script>` with an API call to your backend.

## Accessibility & Improvements

- Add `aria-*` labels and roles for modals and interactive controls to improve screen reader support.
- Server-side contact form processing and CAPTCHA are recommended before using in production to avoid spam.
- Consider optimizing images for web and adding lazy-loading for the gallery.

## License

Add a license file (e.g., `LICENSE`) to this repository if you want to publish it under a specific license.

## Contact

For questions or updates, contact the project owner.

---
