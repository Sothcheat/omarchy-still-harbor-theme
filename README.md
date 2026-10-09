# Still Harbor

A theme for [Omarchy](https://omarchy.org).

```
Still Harbor — a dark theme drawn from a long-exposure photo of a weathered
pier running out into flat, petrol-blue water at dusk.

The mood the picture carries is stillness: mist smoothing the sea, a pale
lavender-grey glow on the horizon, mauve and rose in the cloud bank, and one
saturated band of deep petrol water on the right. So the surfaces are that
water — a near-black that stays blue instead of going neutral — and text is
the pale mist sitting on it. The primary is the lit face of the water.

Every hue below was sampled from the photo (rose cloud #C69CA7 / #D9A5AB,
mauve bank #AE9BB5, deep water #015B87, sky #2E6AA8 / #729CC5, driftwood,
the warm horizon glow); only green has no source in the image and is derived
as a sea-green sitting beside the water's hue.

Lightness is then solved rather than picked, against `lighter_background` —
the lightest surface any of these land on, so the floor holds on every
darker one too. Each solve takes the DARKEST lightness that still clears its
target, which keeps the colors rich instead of washing them toward white.
Every ANSI color clears 5.6:1 (brown, deliberately dim, 4.6:1) and the
bright variants clear 7.8:1 with more chroma. Foregrounds run 5.6:1 (muted)
to 16.8:1 (bright). No two hues are closer than 13.3 CIEDE2000, so nothing
reads as a near-duplicate of its neighbour.
```

## Install

```bash
omarchy theme install https://github.com/Sothcheat/omarchy-still-harbor-theme
```

This clones the theme into `~/.config/omarchy/themes/still-harbor` and applies it. Switch back any time with `omarchy theme set <name>`.

## Contents

- `colors.toml`: the palette. Omarchy generates every app's theme (terminals, Hyprland, Neovim, ...) from it.
- `icons.theme`: the GTK icon theme to use.
- `backgrounds/`: wallpapers. Cycle them with `omarchy theme bg next`.
