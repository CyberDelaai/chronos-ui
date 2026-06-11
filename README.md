# CHRONOS

**Cyberpunk Monthly Calendar Constructor** — a free, in-browser tool that builds a
Cyberpunk 2077-styled monthly calendar and exports it as a clean PNG. Great for TTRPG
game masters and netrunner handouts.

## Features

- **Pick any month / year** and render a styled monthly grid.
- **Year mode** — switch the VIEW toggle to YEAR for a full-year poster of 12
  mini-months, in a 4×3 or 3×4 lattice (always rendered at L size, 2× export).
- **PNG export** — one click saves the calendar as a transparent-corner PNG.
- **Color controls** — set the **Main** (grid/frame) and **Accent** (text/glow) colors
  from 19 preset swatches per palette, or pick any custom color.
- **Day highlights** — click a day to cycle a highlight through 5 colors,
  ctrl+click to stamp the last color, right-click to clear, ctrl+right-click to
  clear all; marks persist per date and export with the PNG.
- **Size presets** — `S` / `M` / `L` cap the calendar width; the exported PNG width
  matches the on-screen `// PREVIEW: NxMpx` label (L renders at 2× for crisper output).
- **First weekday toggle** — start the week on Monday or Sunday.
- **Weekend highlighting** — independently highlight Saturday and/or Sunday.
- **Custom background** — upload, paste, or drag-and-drop an image onto the
  calendar; crop it to the calendar's aspect (with recrop), tune brightness,
  and it exports with the PNG.
- **Themes** — collapsible left **THEMES** drawer with live hover-preview;
  ships DEFAULT and a Y2K **BUBBLEGUM** theme (glossy candy bubble cells,
  scoop-free round frame, gradient day numbers). Each theme keeps its own
  Main/Accent color memory.
- **8 languages** — separate UI language (top-right) and calendar language
  (config panel): EN, RU, FR, DE, ES, IT, JA, ZH. Calendar month/weekday names
  come from the browser's Intl API.
- **Self-contained fonts** — JetBrains Mono is embedded as base64 `@font-face` rules
  (latin, latin-ext, cyrillic), so the typeface renders correctly in the exported PNG
  without any external font fetch. JA/ZH calendars fall back to a system font.

## Usage

Open `index.html` in any modern browser — there is no build step. Pick a month, tweak
the colors and layout, then click **⬇ SAVE PNG**.

## Built with

- [augmented-ui](https://augmented-ui.com/) — clipped/beveled cyberpunk panel styling
- [html-to-image](https://github.com/bubkoo/html-to-image) — DOM → PNG export
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — embedded base64 webfont

## Version

`1.2.5`

## License

[MIT](LICENSE) © 2026 CyberDelaai
