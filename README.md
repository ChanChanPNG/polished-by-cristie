# Polished by Cristie

A static portfolio and service menu for a nail artist in West Jordan, Utah. Visitors can browse Cristie’s work, find the price of each service, and start an appointment inquiry by text or Instagram. Cristie confirms appointments directly.

## Local preview

From this folder, run `python3 -m http.server 8765 --bind 127.0.0.1` and open [the local preview](http://127.0.0.1:8765/). Refresh after editing. The site has no build step or external runtime dependencies.

## Editing

- `index.html` contains the portfolio, services, story, and contact links.
- `assets/site.css` contains the shared design. `assets/` also contains the optimized site images, icons, and Wayfinder logo. The original portfolio photos remain in `work/`.
- `privacy-policy/`, `terms-of-service/`, `sms-policy/`, and `anti-spam/` contain the policy pages. Update the footer across all five pages if any shared link changes.

## Release

Built and reviewed locally on November 9, 2026. The preview checks covered responsive reflow, booking navigation, opening a portfolio photo, and following all four footer policy links. Text and Instagram destinations were checked against the supplied details. Message delivery and testing on physical mobile devices remain open.

Cristie owns pricing, photos, and the appointment workflow. Confirm the policy drafts with Cristie before publishing. Once a production domain is selected, configure the domain and HTTPS, add canonical and share URLs, and verify the live site and its contact paths. Production performance and a full accessibility review remain open.
