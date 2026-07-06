# Gradient Themes


<p align="center">
  <img src="images/showcase-dark.png" width="48%" alt="Gradient (dark) variants - Blue, Red, Emerald, Violet, Gold, Pink, Cyan, Slate">
  <img src="images/showcase-pastel.png" width="48%" alt="Pastel variants of the same colours">
</p>
<p align="center"><sub>Gradient (dark) &middot; Pastel - eight of the twenty colours, applied per section to standard tile cards</sub></p>

Home Assistant themes with diagonal gradient card backgrounds in twenty colours, each available in two variants: **Gradient** (dark, rich tones with white text) and **Pastel** (light, soft tones with dark text). Forty themes in total.

Every card gets the gradient background with matched text, icon, slider and toggle colours, no borders and a soft shadow. Colours: Blue, Sky, Cyan, Teal, Emerald, Green, Lime, Gold, Amber, Orange, Red, Crimson, Pink, Magenta, Purple, Violet, Indigo, Midnight, Steel, Slate — as `Gradient <Colour>` (dark) and `Pastel <Colour>` (light). Each theme also exposes the raw gradient as `--card-gradient` for reuse in card-mod or custom cards.

## Installation

1. HACS → menu (⋮) → **Custom repositories** → add `https://github.com/mycrouch/gradient-themes`, category **Theme**.
2. Download **Gradient Themes**, then reload themes (Developer Tools → YAML → Themes) or restart HA.
3. Requires `frontend: themes: !include_dir_merge_named themes` in `configuration.yaml` (already present if you use any HACS theme).

## Usage

Pick a theme per dashboard (dashboard settings), per view (view settings → theme), or globally in your user profile. Themes can also be applied per **section** (section settings) or per **card** where the card supports it - the ecovacs-vacuum-card below has a built-in per-card theme picker. Mixing variants per view works well — e.g. Cool for climate, Slate for utilities.

## Related projects

| Repo | What it is |
|---|---|
| [hass-airtouch](https://github.com/mycrouch/hass-airtouch) | Polyaire AirTouch 4/5 integration (fork) with a direct-connection mode for consoles on a different subnet/VLAN |
| [airtouch-card](https://github.com/mycrouch/airtouch-card) | Lovelace card for AirTouch 4/5 - console-style zone control with GUI editor and auto-discovery |
| [airtouch-gradient-themes](https://github.com/mycrouch/airtouch-gradient-themes) | 20 gradient dashboard themes matching the card styling |
| [ecovacs-vacuum-card](https://github.com/mycrouch/ecovacs-vacuum-card) | Ecovacs/Deebot vacuum card with per-card theming (default / installed theme / manual gradient) |

## License

MIT
