# Nasrin Kunhimoidu — Personal Portfolio

A responsive single-page portfolio using HTML, CSS and vanilla JavaScript. It contains Nasrin's supplied photographs and facts from her CV and messages. No dependency installation is required.

## Edit content

Edit `dist/content.js` for education, skills, project descriptions, experience, contact information and journey milestones. Add LinkedIn or GitHub URLs to their empty fields when available. Certificates are an empty array until authentic assets are supplied. A certificate entry uses `title`, `issuer`, `date`, and `image` (a local path under `dist`).

Run `node scripts/render-static.cjs` after content changes to refresh the readable, search-friendly HTML. The script also validates local assets, section anchors and duplicate IDs.

`dist/app.js` contains reusable rendering and interactions. `dist/style.css` contains responsive styles and motion. Hero copy and layout can be edited in the `.hero` template in `dist/app.js` before refreshing static HTML.

## Preview

Serve `dist` using any static HTTP server, for example `python -m http.server 5173 --directory dist`.

## Contact behavior

The validated form prepares a mailto draft in the visitor's email app. It does not silently send, store messages, or claim a message was delivered. The direct email and telephone links are also available.

## Content provenance

- Four original photographs supplied by Nasrin; resized and JPEG-compressed for web delivery. CSS framing and shading preserve the actual images.
- Education, project details, experience, email and telephone: supplied CV.
- MySQL, Excel, mobile app development, communication, leadership and teamwork: confirmed in the conversation.
- MCA is in progress, with expected graduation in March 2027. BCA was completed in 2025.
- Project cover graphics are typographic system overviews, not invented product screenshots. AI features described in the CV remain explicitly identified as future scope.
- No certificate images, LinkedIn or GitHub profile URLs were supplied.
- Visual reference: the supplied Instagram reel, used for its portrait-led, bold, dark hero composition.

## Accessibility and performance

Semantic headings, a skip link, keyboard-accessible dialogs, focus restoration, accessible mobile navigation, form validation, responsive images, lazy loading, restrained animations and reduced-motion support are included. There are no third-party frontend libraries, external font requests or trackers.
