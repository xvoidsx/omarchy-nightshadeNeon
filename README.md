# omarchy-nightshadeNeon

The navi theme, as a plain Omarchy theme — no navi-specific wiring, no
changes needed to use it anywhere an Omarchy theme works.

## Install in Omarchy

```
omarchy theme install https://github.com/xvoidsx/omarchy-nightshadeNeon.git
```

The installer clones this repo straight into
`~/.config/omarchy/themes/nightshadeneon/`, so the theme files live at
the repo root: `colors.toml` plus `backgrounds/`. That root layout is
required — a nested `themes/nightshadeNeon/` directory is not picked up.

## Use it in omalauncher

Omalauncher reads the same `~/.config/omarchy/themes/` directory, so once
installed above, the theme applies to the launcher and to its Linux apps
with zero conversion. Backgrounds sort by name; the first one is the
default.

## Contents

- `colors.toml` — pink `#ff10f0` accent, neon green `#39ff14` success,
  cyan `#00ffff`, on a near-black violet `#07040f` base
- `backgrounds/01-lain-hairclip-neon.png` — the default: hairclip Lain, neon
- `backgrounds/02-close-the-world-neon.png`
- `backgrounds/03-duskline.png`
- `backgrounds/04-lain-wired-constellation.png`
- `backgrounds/05-present-day.png`

Wallpapers are navi / xvoidsx artwork (Lain, the wired). No
`alacritty.toml` is shipped on purpose: `colors.toml` is the current
colour source, and Omarchy refuses terminal configs from installed
themes anyway.
