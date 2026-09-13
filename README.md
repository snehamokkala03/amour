# L'Hotel Trois Amours — Invitation Site

A two-page invitation site for the murder mystery party.

## Files
- `index.html` — the invitation, date/time/location, and RSVP form
- `about.html` — About Us tab (placeholder: "Coming Soon")
- `assets/style.css` — shared styling
- `assets/logo.svg` — the three-roses gold-outline crest

## Publish it with GitHub Pages
1. Create a new GitHub repo (e.g. `trois-amours-party`).
2. Upload all the files in this folder, keeping the `assets/` folder structure intact.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," pick the `main` branch and `/ (root)` folder, then save.
5. GitHub will give you a live URL (usually `https://<your-username>.github.io/<repo-name>/`) within a minute or two.

## Notes
- The RSVP form is front-end only — submitting shows a confirmation message but doesn't email or store anything yet. If you want real RSVPs collected, the easiest options are wiring the form to a free service like Formspree or Google Forms, or asking guests to reply by text/email.
- Text says **8:00 PM – 12:00 AM** (assuming you meant the party runs past midnight) — edit the `<span>` inside the "details" section of `index.html` if you meant something else.
