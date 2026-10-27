![Omnia Ex Machina](images/cover.png)

# Omnia Ex Machina

**Omnia Ex Machina** is a machine-geometric Obsidian theme inspired by Cupertino, featuring architectural typography, squared surfaces, precision hairline dividers, and a restrained visual language. Built around Paper & Ink light mode and Graphite & Phosphor dark mode, with customizable signal accents and carefully styled workspace components.

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Donate-FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/tuliopc23)

![Dark mode](images/dark.png)

## Install

**Community themes** (once listed): Settings → Appearance → Themes → search "Omnia Ex Machina".

**Manual:** copy `theme.css` and `manifest.json` into `<vault>/.obsidian/themes/Omnia Ex Machina/`, then pick the theme in Settings → Appearance.

## Type system

No fonts ship with the theme — zero remote assets, fully self-contained. Stacks degrade to system faces:

| Role | Preferred | Fallback |
|---|---|---|
| Titles | ABC Diatype Expanded Ultra | SF Pro Display → Helvetica Neue |
| Headings | ABC Diatype Expanded Black | SF Pro Display → Helvetica Neue |
| Body | ABC Diatype Extended | SF Pro Text → Helvetica Neue |
| Interface & labels | PP Watch | condensed mono → Ioskeley Mono NF |
| Code | Ioskeley Mono | JetBrains Mono / SF Mono → Menlo |

- **ABC Diatype** (commercial): [abcdinamo.com](https://abcdinamo.com)
- **PP Watch** (commercial): [pangrampangram.com](https://pangrampangram.com)
- **Ioskeley Mono** (free): an Iosevka-built Berkeley-Mono-style variant — build via the [Iosevka customizer/docs](https://github.com/be5invis/Iosevka)

The theme reads any installed matching family names automatically; font names are also overridable per-role in Style Settings.

## Style Settings

43 settings in 5 groups (requires the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin):

- **Typography** — per-role font-family overrides, measure
- **Surfaces** — radius, density, line width, machine tags, sticky table headers, table grid lines, row scanlines, codeblock language banners, spec-card metadata, heading rules, Grenadier headings, Signal accent preset
- **Chrome & desktop** — titlebar, tabs, status bar treatments
- **Editor** — line numbers, guides, cursor, selection behavior
- **Accessibility** — contrast and motion accommodations

**Signal accent** re-maps the accent hue globally — links, tags, list markers, checkboxes, active states — in both themes: Grenadier (default), Cobalt, Amber, Viridian.

## Tables & Helper Classes

The theme implements an architectural ledger table system with sticky headers, alternating row striping, hover scanlines, and tabular figures. You can customize table behavior per-note via frontmatter `cssclasses:`

| Class | Effect |
|---|---|
| `table-lines` | Hairline vertical grid dividers between columns |
| `table-striped` | Force ledger zebra striping across alternating rows |
| `table-sticky` | Pin headers to top during vertical scroll |
| `table-tabular` | Enforce full monospace tabular figures for numeric data |
| `table-nowrap` | Prevent cell line wrapping for compact technical sheets |
| `table-compact` | Dense cell padding (0.22em / 0.5em) |
| `table-wide` | Expand table to full container width |

## Machine Callouts

In addition to Obsidian's default callout types, Omnia Ex Machina includes machine-specific plates:

- `> [!spec]` — Blueprint specsheet with accent rail
- `> [!terminal]` — Phosphor CRT terminal block with green monospace prompt
- `> [!log]` — Telemetry & event ledger in monospace
- `> [!register]` — System status & memory register with amber indicator

## Plugin integrations

Passive, class-scoped rules — applied only when the plugin is present, inert otherwise:

| Plugin | Integration |
|---|---|
| Dataview | Ledger tables, pagination buttons, inline fields `[key:: value]`, full `.cards` & `.list-cards` support |
| Obsidian Projects | Squared view tabs, ledger tables, hairline kanban columns, gallery cards |
| Hover Editor | Framed popover window, squared corners, hairline titlebar, classify titles |
| Note Toolbar | Flat machine dock callout, square icon buttons with signal hover states |
| QuickAdd | Squared prompt modals, classify headers, hairline list dividers |
| Templater | Machine prompt modals and square inputs |
| Contribution Graph | Square heatmap cells, classify month/day labels, phosphor accents |
| Outliner | Hairline indentation guides, crisp square bullet registration |
| Breadcrumbs | Classify trail chips, hairline borders, signal link hovers |
| Supercharged Links | Crisp metadata icons and attribute pills |
| Tasks | Per-status accent checkboxes, modal forms, priority colors, date chips |
| Kanban | Squared lanes/cards, classify lane titles, accent drag ring |
| Bases | Hairline table chrome, query and filter toolbar controls |
| Book Search / Media DB | Squared modal dialogs, book covers, classify metadata tags |
| Iconic | `extras/iconic-preset.json` icon set (see below) |
| Calendar | Machine register for the calendar pane |
| Canvas | Classify edge labels, squared nodes |
| Omnisearch | Squared modal/results, classify metadata, accent highlight |
| Charts | Squared canvas frame |
| Excalidraw | Dark-scheme accent lift |

### Iconic preset

Copy `extras/iconic-preset.json` over `.obsidian/plugins/iconic/data.json` in your vault, then restart Obsidian.

![Specimen](images/specimen.png)

## Mobile

Fully responsive: callouts, Kanban, and settings surfaces adapt under `is-mobile`; the iCloud-synced vault keeps desktop and phone on the same file. Density and radius sliders are the two knobs worth touching on small screens.

## Support

If you enjoy Omnia Ex Machina and want to support ongoing development:

<a href="https://www.buymeacoffee.com/tuliopc23" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 48px !important;width: 174px !important;" ></a>

Support Tulio Cunha on Buy Me a Coffee: **[buymeacoffee.com/tuliopc23](https://www.buymeacoffee.com/tuliopc23)**

## Credits
 
Built on the [Cupertino](https://github.com/svnaxis/obsidian-cupertino) theme chassis by [Alexis C](https://github.com/svnaxis) (MIT License). Retains upstream structural foundation with custom typography, geometry, color palettes, and component styling.

## License

MIT — see [LICENSE](LICENSE).
