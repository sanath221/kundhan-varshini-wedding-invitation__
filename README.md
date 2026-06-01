# Kundhan & Varshini — Invitation (static page)

Files added:

- `index.html` — the invitation page with embedded RSVP form.
- `styles.css` — simple styles for layout and responsiveness.

Usage

1. Save the attached invitation image into the `assets` folder as `invitation.jpg`:

   - Create the folder `assets` next to `index.html` if it doesn't exist.
   - Place the attached image file (the one you provided) at `assets/invitation.jpg`.

2. Preview locally (example using Python):

```bash
# from the project folder
python -m http.server 8000
# then open http://localhost:8000/index.html in your browser
```

Notes

- The page embeds the JotForm RSVP using an iframe. The form URL used is `https://form.jotform.com/261511124643043`.
- Metadata (`og:image`) points to `assets/invitation.jpg` so social previews will use the attached image once uploaded to a public URL.
