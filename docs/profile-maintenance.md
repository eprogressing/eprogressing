# Profile maintenance

This repository supplies the profile README for [eprogressing](https://github.com/eprogressing).

## Assets and links

- Keep the Little Prince cover at `assets/hero.svg`; the README references it directly.
- Navigation and research badges use Shields.io. Keep link destinations on the surrounding `<a>` elements and provide readable image alt text.
- Each competition card links to an explicit anchor in `AWARDS.md`. Preserve that anchor when editing its heading.
- Award cards have desktop and `-mobile.svg` variants. Update both variants when changing the displayed award name, year, or result.
- The SVG cards are illustrations of the award records. Source links belong in `AWARDS.md`; actual certificates can be added there when available.

## Before publishing

1. Confirm every relative image path exists in the repository.
2. Open each competition card and confirm it reaches the corresponding award record.
3. Check the rendered profile at desktop and phone widths for wrapping and horizontal overflow.
4. Check the cover, badges, and award cards in both light and dark mode.

GitHub controls the profile's available width and Markdown rendering. An introduction that fits on one desktop line will wrap on narrower screens. Prefer short, readable text and verify the actual GitHub page after publishing.

## Editing a Shields badge

In a Shields.io badge URL, the label, message, and color form the `/badge/` path. Keep `style=for-the-badge` consistent within each row. When writing a URL inside an HTML attribute in the README, encode query separators as `&amp;`. To change where a badge opens, edit its surrounding `<a href="...">` rather than the image URL.

## Adding an award record

Choose a stable award ID and add its explicit anchor and source links to `AWARDS.md`. Add the desktop and mobile SVG variants under `assets/`, then link the new README card to that same anchor. Check the card image, its alt text, and the destination together before publishing.

## Repository notifications

Notification preferences belong to each GitHub account, not to the README. To stop notifications from this repository, sign in with the account receiving the emails and choose **Watch → Ignore** on the repository page. Revoking an application's authorization does not unsubscribe that account from repository activity.

Previously delivered emails remain in the mailbox. When investigating a newly received notification, compare the email's timestamps with the linked PR or discussion activity before assuming that a new change was made. Keep useful PR history and accepted answers rather than deleting them to suppress notifications.
