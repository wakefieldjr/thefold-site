# thefoldapp.com

The Fold's own website. Right now it is one page: the join page, served at `/` and `/join`.

- **Static files, no build.** `index.html`, `site.css`, `thanks/`, `fonts/`, `favicon.svg`. Netlify publishes the repo root (`netlify.toml`).
- **The look is the app's** (Charcoal Glass): charcoal ground, violet accent, Fraunces headlines, DM Sans text. Fonts are served from this site (OFL licences in `fonts/`), so a visit makes no request to anyone else.
- **No analytics, no tracking, no third-party scripts.** The Content-Security-Policy in `netlify.toml` enforces it.
- **The form** is a Netlify Form named `join`: what they want (host this season or the waitlist), name, email or phone, and what they host. Netlify keeps submissions; notifications go to hello@thefoldapp.com (set in Netlify under Forms, Form notifications). A hidden honeypot field (`company`) catches bots.
- **Screenshots** are placeholders until real ones are taken on the preview app with invented data. Put them in `screens/` and swap each placeholder for the `<img>` noted in `index.html`. Never mockups, never real guests.
- **The logo** is the current "one of the seats" mark until the final one exists.

The words come from the "Join page words" doc; the design is direction B, "the open door".
