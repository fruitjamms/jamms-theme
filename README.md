# jamms for zed

a two-mode zed theme using the jamms palette:

- pink: `#ff29a7`
- orange: `#ff9e28`
- lime: `#ddff00`
- green: `#21ff8c`
- blue: `#3138ff`
- light background: `#ffffff`
- dark background: `#000000`

## install as a dev extension

1. unzip this folder somewhere permanent.
2. open zed.
3. open the command palette.
4. run **`zed: install dev extension`**.
5. select the **`jamms-theme`** folder — the folder containing `extension.toml`.
6. open the theme selector with **cmd-k cmd-t** on macos or **ctrl-k ctrl-t** elsewhere.
7. choose **jamms light** or **jamms dark**.

for automatic system switching, add this to zed's `settings.json`:

```json
{
  "theme": {
    "mode": "system",
    "light": "jamms light",
    "dark": "jamms dark"
  }
}
```

## light mode color strategy

the light theme deliberately uses the original neon lime and green at full intensity for
highlights, selections, borders, and accent surfaces.

for syntax text on white, it uses brighter "ink" variants of those same hues:
- lime ink: `#8aa100`
- green ink: `#00a95e`

this keeps the light mode much more neon while preventing the palest colors from disappearing
completely against white.

## repository

https://github.com/fruitjamms/jamms-theme
