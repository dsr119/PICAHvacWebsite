# PICA HVAC website

The website for PICA HVAC, Scranton, PA. It's a plain static site (HTML, CSS and a little JavaScript) with no build step, so any static host can serve it as-is.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home: hero with click-to-call, services overview, about, testimonials, heating oil partner |
| `services.html` | Detail for each service, with anchors `#heating`, `#cooling`, `#water-heaters`, `#backflow` |
| `contact.html` | Contact details and the "Request Service" form |
| `thanks.html` | Shown after the form is sent |

Shared styles are in `css/styles.css`, the mobile menu script in `js/main.js`, and the logo and favicon in `assets/`.
The header and footer are repeated in each page, so change them in all four files.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Hosting

The contact form is set up for [Netlify Forms](https://docs.netlify.com/forms/setup/): deploy this repo to Netlify and submissions show up in the Netlify dashboard (and can be emailed to you). On another host, point the form's `action` at a form service such as Formspree instead.

## Logo

`assets/logo.png` was cut out from a photo of the van decal. Swap in an original vector logo file if one turns up.
