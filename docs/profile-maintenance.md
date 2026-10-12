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
