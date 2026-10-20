# LET Attendance Dashboard Guide — Jekyll / Markdown

A Markdown-first, multi-page starter site based on the supplied *LET Attendance Dashboard* manual, version 4.0.0. Designed for GitHub Pages and a public repository.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select your default branch and `/ (root)`, then save.
4. Wait for GitHub Pages to publish the site, then review the published URL.

The content is written in Markdown. Jekyll's `minima` theme provides the shared page layout and header navigation; `_includes/head-custom.html` loads the small CSS file for visible keyboard focus and image styling.

## Public-safe images

All 16 image assets are recreated SVG mock-ups using fictional example values. The original embedded screenshots from the DOCX are not included. Do not add the source DOCX, original screenshots, student/staff data or internal links to the public repository.

## Accessibility and alt-text

Each Markdown image has descriptive alternative text. `ALT-TEXT-REGISTER.md` records the published alt text and how each image was handled. Because each original screenshot was replaced by a new illustration, the public alt text is matched to the new image while retaining the original instructional purpose. Review each description when editing an illustration.

This starter project has not been certified as WCAG conformant. Before release, test heading structure, keyboard navigation, focus visibility, contrast, zoom/reflow and screen-reader output. Use an automated checker and manual testing in the deployed GitHub Pages environment.

## Content accuracy

The guide follows the supplied manual. The manual described Analysis as under development at the time it was written; that qualification is retained. Validate the instructions against the live app before treating the guide as authoritative operational documentation.
