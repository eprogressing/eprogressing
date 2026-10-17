# Profile maintenance

This repository supplies the profile README for [eprogressing](https://github.com/eprogressing).

## Current layout

- Keep the Little Prince cover at `assets/hero.svg`.
- Keep the profile in English, using GitHub's native Markdown typography.
- Navigation links point to the introduction, Projects, Open source, Competition honors, and Contact sections. About links to the native greeting heading's `hi-im-jingming-liang` anchor. The explicit `about` anchor is retained for older links.
- Use GitHub's native font for headings and introductions. Keep decorative motion in the existing cover instead of adding text rendered as images.
- Competition honors are text lists grouped by year. Keep the detailed records and evidence links in `AWARDS.md`; exclude school-level awards.
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

Keep `style=flat` and the current muted purple consistent within the compact link row. In HTML attributes, write query separators as `&amp;`. Change the surrounding `<a href="...">` to update a badge's destination; keep meaningful image alt text.

## Adding an award

Add a concise English entry under its year in `README.md` and the corresponding record with source links in `AWARDS.md`. Keep awards from the same competition together. Preserve existing reference links and anchors when updating the record.

## Repository notifications

Notification preferences belong to each GitHub account, not to the README. To stop notifications, use **Watch → Ignore** while signed in as the receiving account. Revoking an application's authorization does not unsubscribe the account from repository activity.

When investigating an email, compare its timestamps with the linked activity. Preserve useful PR history and accepted answers rather than deleting them to suppress notifications.
