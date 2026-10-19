# FindoraDaily public website — V1

Public-facing static website for FindoraDaily, separate from the private `FindoraDaily/findoradaily-ai` operations repo. **No affiliate links, products, reviews, forms, analytics, or payment flows are active.**

## Files
- `index.html` — landing page / launch statement
- `about.html` — editorial mission and standards
- `disclosure.html` — affiliate disclosure and current status
- `contact.html` — honest holding page until an owner-controlled business contact exists
- `privacy.html` — current static-site privacy notice
- `404.html` — error page
- `assets/` — original CSS, tiny JavaScript for footer year, SVG brand icon

## Publish for $0 using GitHub Pages
1. Keep the existing `findoradaily-ai` repository private.
2. In this public repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then `main` and `/(root)`; save.
4. When live, the expected project site URL is `https://findoradaily.github.io/findoradaily-site/` (verify with Pages settings; don't assume active until tested).
5. Open Home, About, Disclosure, Contact, and Privacy in desktop and mobile browsers to validate links and layout.

### Safe publication checklist
- The public repo includes only intended website files, never secrets, keys, private customer information, affiliate reports or databases.
- The Findora name remains provisional pending trademark clearance.
- Before contacting affiliate programs, replace the Contact holding notice with a real, owner-monitored contact method and update Privacy if new tools are added.
- Independently verify any future product claims and permitted imagery. Disclose affiliate partnerships near actual links as required.
- No paid advertising or automatic publishing is configured.

## Preview locally
Run `python -m http.server 8000` from this directory, then open `http://localhost:8000/`.
