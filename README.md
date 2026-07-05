# Michigan Mini & Toy Poodles Website

Static website for Michigan Mini & Toy Poodles, ready to publish with GitHub Pages.

## GitHub Pages Setup

1. In GitHub, open `Settings` -> `Pages`.
2. Under `Build and deployment`, choose `Deploy from a branch`.
3. Select branch `main` and folder `/root`.
4. Save. GitHub will publish the site after the first Pages build finishes.

The site entry point is `index.html`.

## Contact Form

GitHub Pages cannot process form submissions by itself because it only serves static files.

To make the form actually send inquiries, use one of these:

- Formspree
- Basin
- Getform
- Google Forms
- A custom backend/API

After creating a form endpoint, update the `action` attribute in `contact.html`.

Current placeholder:

```html
action="https://formspree.io/f/REPLACE_WITH_FORM_ID"
```

Replace `REPLACE_WITH_FORM_ID` with the actual form id from the provider.

## Health Document Link

The Health page has a future Google Doc/Drive placeholder button in `health.html`.

Replace:

```html
href="#"
```

with the final Google Doc or Google Drive sharing link.
