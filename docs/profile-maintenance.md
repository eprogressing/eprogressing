# Profile maintenance

This repository supplies the profile README for [eprogressing](https://github.com/eprogressing).

## Current layout

- Keep the Little Prince cover at `assets/hero.svg`.
- Keep the profile in English, using GitHub's native Markdown typography.
- A compact, left-aligned text navigation row sits below the cover, linking to About, Competition honors, Open source, and Contact.
- The introduction begins in About. Keep the greeting, affiliation, one concise research paragraph, and personal/open-source introduction together in this section.
- The terminal-style greeting is a local animated SVG at `assets/intro-about-code.svg`, using an explicit system monospace stack at size 18. Its light/dark colors are `#716083` and `#BBAACD`. The animation includes a reduced-motion fallback and does not call an external typing service.
- Keep the Website, CV, ORCID, and Email badges in one left-aligned row at the end of About, before Competition honors. The lab link belongs in the affiliation text.
- Keep Triangle Light Maze Solver as a brief first-person authorship mention under Lamplighter Commons in Open source; do not give it a standalone Projects section.
- Competition honors appear immediately after About and before Open source to foreground technical achievements. They are text lists grouped by year. Keep the detailed records and evidence links in `AWARDS.md`; exclude school-level awards except the explicitly retained TRAE Vibe Coding Workshop second-place result.
- Existing award illustrations are retained as archived assets. The README no longer displays the award wall; adding an award does not require generating images.
- Website, CV, ORCID, email, project, and organization links should point to real, available destinations.
- Only add projects, publications, affiliations, and funding links when their details are confirmed. Do not publish placeholders for unreleased projects or unavailable sponsorship accounts.

## Before publishing

1. Compare the current remote version before editing so that other changes are preserved.
2. Confirm every relative image and document path exists.
3. Verify navigation anchors and external link destinations.
4. Check the rendered GitHub profile at desktop and phone widths for wrapping and horizontal overflow.
5. For visual changes, check the cover and badges in light and dark mode.

GitHub controls the profile's width and Markdown rendering. Prefer short, readable text over custom text rendered into images.

## Editing badges

Keep `style=flat-square` throughout the compact contact row. Use muted blue `455F7B` for Website, purple `756080` for CV, green `5B7C2F` for ORCID, and rose `8A5D63` for Email. In HTML attributes, write query separators as `&amp;`. Change the surrounding `<a href="...">` to update a badge's destination; keep meaningful image alt text.

## Adding an award

Add a concise English entry under its year in `README.md` and the corresponding record with source links in `AWARDS.md`. Keep awards from the same competition together. Preserve existing reference links and anchors when updating the record.

## Repository notifications

Notification preferences belong to each GitHub account, not to the README. To stop notifications, use **Watch → Ignore** while signed in as the receiving account. Revoking an application's authorization does not unsubscribe the account from repository activity.

When investigating an email, compare its timestamps with the linked activity. Preserve useful PR history and accepted answers rather than deleting them to suppress notifications.

## Competition naming and affiliation sources

Use the NBJL personal page and the author-provided presentation as recorded in `AWARDS.md`. Preserve parent competition names, contest tracks, and regional divisions. Do not shorten names merely to fit a visual layout. Keep PhD study explicitly prospective with the expected 2027 start; retain all three research areas from the NBJL personal page.
