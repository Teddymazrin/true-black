# Marketplace assets

Before publishing to the Marketplace, add the following files to this directory:

## `icon.png` (REQUIRED)
- **Exactly 128×128 pixels**
- PNG format
- Referenced from `package.json` as `"icon": "media/icon.png"`
- Suggested design: solid `#000000` background with the accent character (e.g., a single white glyph) so it reads at thumbnail size

## Screenshots (recommended)
- `screenshot-editor.png` — code editor with active syntax highlighting
- `screenshot-customize.gif` — animated GIF showing `trueBlack.accentColor` live-updating
- `screenshot-terminal.png` — the integrated terminal with ANSI colors

Reference these from the root `README.md` to make the Marketplace listing compelling.

## Notes
- The Marketplace shows the icon at 128×128 in the extension card and 32×32 in search results. Design for both scales.
- Screenshot files should be PNG (lossless) and sized reasonably (under 1MB each).
- GIFs drive install rate more than static screenshots — prioritize a short (5–10 second) GIF demonstrating live customization.
