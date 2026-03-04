# Dev Portfolio

A modern single-file developer portfolio website built with plain HTML, CSS, and JavaScript.

## Overview

This project is a responsive personal portfolio for **Yash Bisht** featuring:

- Hero section with role and CTA
- Skills section
- Project showcase
- About section
- Experience section
- Development process section
- Contact section with social links and form UI

## Tech Stack

- HTML5
- CSS3 (custom properties, responsive layout, animations)
- Vanilla JavaScript (UI interactions and effects)
- Google Fonts (`Plus Jakarta Sans`, `DM Mono`)

## Key UI Features

- Animated preloader
- Scroll-triggered fade-in transitions
- Custom cursor for pointer devices
- Sticky navigation with active section highlighting
- Mobile drawer navigation
- Back-to-top button
- Interactive contact form button state

## Project Structure

```text
.
+-- index.html
```

## Run Locally

No build step or dependencies are required.

1. Clone or download the repository.
2. Open `index.html` directly in a browser.

Optional local server (recommended for cleaner local testing):

```bash
# Python 3
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Customization

Update content directly inside `index.html`:

- Personal details and metadata in the `<head>` section
- Section copy (hero, about, experience, projects)
- Contact links (`mailto`, GitHub, LinkedIn)
- Theme tokens in `:root` CSS variables

## Deployment

Because this is a static site, you can deploy it on:

- GitHub Pages
- Netlify
- Vercel (static)
- Cloudflare Pages

## Notes

- The contact form is currently UI-only and does not submit to a backend.
- If text appears with odd characters, save the file in UTF-8 encoding and ensure your editor/browsers use UTF-8.
