MUQEET AHMED — COMPLETE WEBSITE SOURCE

This ZIP contains the exact website files used for the final live deployment.

CONTENTS
- index.html: page content, structure, metadata and base styles
- assets/: all stylesheet, JavaScript, logo, texture and sample-image files
- assets/portfolio-refinements.css: final layout and responsive adjustments
- assets/workflow-animation.js: hero workflow animation
- assets/process-animation.js: process-section animation
- assets/work-sheets.js: project popup and zoom behavior
- assets/portfolio/: full-resolution project screenshots and thumbnails

RUN LOCALLY
1. Extract the ZIP into one folder.
2. Open a terminal in that folder.
3. Run: python -m http.server 8000
4. Open http://localhost:8000 in your browser.

No installation or build step is required. Use a local web server because
asset paths start at /assets/. Opening index.html directly from disk will
not resolve those paths.

HOSTING
Upload index.html and the entire assets folder to the root of a static
website host. Keep their paths unchanged.

EDITING
Edit index.html for text and project entries. Each project button's
data-sheet value matches a template ID near the bottom of index.html.
Keep those IDs in sync when adding samples. Edit the CSS files in assets
for theme, layout and responsive behavior.

The page includes 12 project samples, company logos, tool logos, two
animated workflows and responsive navigation. The original supplied
screenshots are included in the portfolio folder.

Live website:
https://abdul-muqeet-lead-portfolio.brosatworkk.chatgpt.site

FINAL UPDATE
Smartlead Campaign is second and UK Email Campaign is eleventh. The hero
services use individual badges. Both contact buttons link to
https://www.upwork.com/freelancers/muanimator
Tool logos share an aligned full-width grid and matching visible heights.
