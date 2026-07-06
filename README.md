# Gradient Themes

Home Assistant themes with the diagonal gradient card styling from the [AirTouch Card](https://github.com/mycrouch/airtouch-card), in twenty selectable colours.

| Theme | Gradient |
|---|---|
| Gradient Blue | deep navy - blue |
| Gradient Sky | navy - sky blue |
| Gradient Cyan | dark teal - cyan |
| Gradient Teal | slate blue - teal |
| Gradient Emerald | deep green - emerald |
| Gradient Green | forest - green |
| Gradient Lime | olive - lime |
| Gradient Gold | bronze - gold |
| Gradient Amber | dark bronze - amber |
| Gradient Orange | umber - orange |
| Gradient Red | dark ember - orange red |
| Gradient Crimson | oxblood - crimson |
| Gradient Pink | plum - pink |
| Gradient Magenta | aubergine - magenta |
| Gradient Purple | deep violet - purple |
| Gradient Violet | midnight - violet |
| Gradient Indigo | navy - indigo |
| Gradient Midnight | near-black - midnight blue |
| Gradient Steel | charcoal - steel blue |
| Gradient Slate | graphite - slate grey |

Every card gets the gradient background with white text, tuned icon/slider/toggle colours, no borders and a soft shadow — the whole dashboard takes on the AirTouch console look. Each theme also exposes the raw gradient as `--card-gradient` for reuse in card-mod or custom cards.

## Installation

1. HACS → menu (⋮) → **Custom repositories** → add `https://github.com/mycrouch/airtouch-gradient-themes`, category **Theme**.
2. Download **Gradient Themes**, then reload themes (Developer Tools → YAML → Themes) or restart HA.
3. Requires `frontend: themes: !include_dir_merge_named themes` in `configuration.yaml` (already present if you use any HACS theme).

## Usage

Pick a theme per dashboard (dashboard settings), per view (view settings → theme), or globally in your user profile. Mixing variants per view works well — e.g. Cool for climate, Slate for utilities.

## Companions

- [AirTouch Card](https://github.com/mycrouch/airtouch-card) — Lovelace card for AirTouch 4/5 zone control (the origin of these gradients).
- [hass-airtouch fork](https://github.com/mycrouch/hass-airtouch) — AirTouch integration with direct-connection mode for cross-VLAN setups.

## License

MIT
