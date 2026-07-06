# Gradient Themes

Home Assistant themes with the diagonal gradient card styling from the [AirTouch Card](https://github.com/mycrouch/airtouch-card), in six selectable colours: Blue, Red, Amber, Cyan, Teal and Slate.

| Theme | Gradient |
|---|---|
| Gradient Blue | deep navy → blue |
| Gradient Red | dark ember → orange |
| Gradient Amber | dark bronze → amber |
| Gradient Cyan | dark teal → cyan |
| Gradient Teal | slate blue → teal |
| Gradient Slate | graphite → slate grey |

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
