# Nasrin Kunhimoidu — Personal Portfolio

A responsive cinematic portfolio using HTML, CSS and vanilla JavaScript. It contains Nasrin's supplied photographs, professional portrait treatment, certifications, CV, social profiles, and confirmed personal details. No dependency installation is required.

**Live portfolio:** [folio-graduation-studio.nasrin-kunhimoiduu.chatgpt.site](https://folio-graduation-studio.nasrin-kunhimoiduu.chatgpt.site/)

The experience includes a photographic Milky Way background, animated starfield, responsive glass UI, interactive portrait treatment, project case studies, ten certificates, a graduation gallery, resume download, and accessible reduced-motion behavior.

## Edit content

Edit `dist/content.js` for education, skills, project descriptions, certifications, activities, interests, contact information, social links, resume path, and journey milestones. A certificate entry uses `title`, `issuer`, `date`, `image`, and `description`.

Run `node scripts/render-static.cjs` after content changes to refresh the readable, search-friendly HTML. The script also validates local assets, section anchors and duplicate IDs.

`dist/app.js` contains reusable rendering and interactions. `dist/style.css` contains the foundation; `dist/premium.css` contains the premium motion, loader, gallery, resume, certification, and cursor layer. Hero copy and layout can be edited in the `.hero` template in `dist/app.js` before refreshing static HTML.

## Preview

Serve `dist` using any static HTTP server, for example `python -m http.server 5173 --directory dist`.

## Contact behavior

The validated form prepares a mailto draft in the visitor's email app. It does not silently send, store messages, or claim a message was delivered. The direct email and telephone links are also available.

## Content provenance

- Original professional and graduation photographs supplied by Nasrin; resized and JPEG-compressed for web delivery. CSS framing and shading preserve the actual images.
- Education, project details, experience, email and telephone: supplied CV.
- MySQL, Excel, mobile app development, communication, leadership and teamwork: confirmed in the conversation.
- MCA is in progress, with expected graduation in March 2027. BCA was completed in 2025.
- Project cover visuals represent the AeroNexus airport system and KIMS immigration-management system without claiming to be product screenshots. AI features described in the CV remain explicitly identified as future scope.
- Ten supplied certificate images are presented with descriptive metadata and an accessible lightbox.
- LinkedIn and Instagram links were supplied and are included. No GitHub profile URL was supplied.
- Visual reference: the supplied Instagram reel, used for its portrait-led, bold, dark hero composition.

## Accessibility and performance

Semantic headings, a skip link, keyboard-accessible dialogs, focus restoration, accessible mobile navigation, form validation, responsive images, lazy loading, restrained animations and reduced-motion support are included. There are no third-party frontend libraries, external font requests or trackers.
