# Jamms for Zed

A two-mode Zed theme using the Jamms palette:

- Pink: `#FF29A7`
- Orange: `#FF9E28`
- Lime: `#DDFF00`
- Green: `#21FF8C`
- Blue: `#3138FF`
- Light background: `#FFFFFF`
- Dark background: `#000000`

## Install as a Dev Extension

1. Unzip this folder somewhere permanent.
2. Open Zed.
3. Open the Command Palette.
4. Run **`zed: install dev extension`**.
5. Select the **`jamms-theme`** folder — the folder containing `extension.toml`.
6. Open the Theme Selector with **Cmd-K Cmd-T** on macOS or **Ctrl-K Ctrl-T** elsewhere.
7. Choose **Jamms Light** or **Jamms Dark**.

For automatic system switching, add this to Zed's `settings.json`:

```json
{
  "theme": {
    "mode": "system",
    "light": "Jamms Light",
    "dark": "Jamms Dark"
  }
}
```

## Light Mode Color Strategy

The light theme deliberately uses the original neon lime and green at full intensity for
highlights, selections, borders, and accent surfaces.

For syntax text on white, it uses brighter "ink" variants of those same hues:
- Lime ink: `#8AA100`
- Green ink: `#00A95E`

This keeps the light mode much more neon while preventing the palest colors from disappearing
completely against white.

## Repository

https://github.com/fruitjamms/jamms-theme
