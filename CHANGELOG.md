# Changelog

## 1.1.0 — 2026-10-27

### Tables & Data Grid
- **Universal Table System**: Complete machine-geometric overhaul across Reading view and Live Preview (`.markdown-rendered`, `.el-table`, `.cm-table-widget`, `.cm-table`).
- **Ledger Aesthetics**: Architectural top/bottom rules (1.5px / 1px), hairline cell dividers, uppercase classify headers in `var(--omnia-font-classify)` with letter-spacing.
- **Tabular Numerals**: Enforced `tabular-nums` for crisp numeric column alignment.
- **Sticky Headers**: Pinned table headers during vertical scrolling (toggleable via Style Settings or `.table-sticky` class).
- **Ledger Scanlines & Hover**: Alternating row striping and interactive hover scanline highlights.
- **Live Preview Controls**: Machine-styled drag handles, row/column addition buttons, and active selection states.
- **Table Helper Classes**: Added `.table-lines`, `.table-striped`, `.table-tabular`, `.table-nowrap`, `.table-compact`, and `.table-wide`.

### Metadata & Spec-Card Properties
- **Spec-Card Container**: Precision hairline container with signal accent registration rail (`omnia-spec-metadata`).
- **Classified Property Keys**: Uppercase classify keys with crisp hairline dividers and focused input halos.
- **Multi-Select Pills**: Machine-squared pills with hairline borders, accent hover states, and clean delete glyphs.
- **Dataview Inline Fields**: Native chip styling for `[key:: value]` inline fields with uppercase classify keys and hairline separators.

### Code Blocks, Math & Callouts
- **Codeblock Language Banners**: Technical classification badge and hairline header separating language label from code (`omnia-code-banner`).
- **Machine Copy Button**: Outlined square action button with signal hover feedback.
- **LaTeX Math Formatting**: Hairline framed formula blocks with paper/graphite tint.
- **Machine Callout Types**: Added `spec` (blueprint specsheet), `terminal` (phosphor CRT prompt), `log` (event ledger), and `register` (status register).

### Extended Plugin Integrations
- **Dataview & Cards**: Deepened table pagination, query status, and full machine-geometric `.cards` and `.list-cards` layout support with aspect ratio modifiers.
- **Obsidian Projects**: Squared view selector tabs, ledger table view, hairline kanban board columns, and gallery cards.
- **Hover Editor**: Framed floating popover with squared chrome, hairline titlebar, and classify title text.
- **Note Toolbar**: Flat machine dock callout styling with square action buttons and signal hover states.
- **QuickAdd & Templater**: Squared prompt modals, classify headers, and hairline list dividers.
- **Contribution Graph**: Square heatmap matrix cells, classify month/day labels, and phosphor accents.
- **Outliner & Breadcrumbs**: Hairline indentation guides, square bullet registration, and classify breadcrumb chips.
- **Supercharged Links & Media DB**: Subtle attribute icons, book search result cards, and media covers.
- **Tasks & Bases Deepening**: Modal forms, priority tags, scheduled/due date chips, and query filter bars.

## 1.0.1 — 2026-10-16

- Prepared theme for official Obsidian Community Theme Gallery submission.
- Updated author URL and repository metadata.
- Refined documentation and Style Settings descriptions to highlight design identity inspired by Cupertino.
- Retained explicit upstream attribution to Cupertino chassis and Alexis C.
- Stabilized release workflow and distribution packaging.

## 1.0.0 — 2026-10-08 — Initial release

- Machine-geometric Obsidian theme: squared corners, hairline rules, Paper/Ink light and Graphite/Phosphor dark palettes, Grenadier signal accent.
- Type system: ABC Diatype Expanded (titles/headings), ABC Diatype Extended (body), PP Watch (labels), Ioskeley Mono (code) — all with system fallbacks; no fonts bundled.
- Style Settings: 38 settings in 5 groups — Typography, Surfaces, Chrome & desktop, Editor, Accessibility — including a Signal accent preset (Grenadier / Cobalt / Amber / Viridian).
- Passive, class-scoped integrations: Iconic, Calendar, Dataview + cards helpers, Tasks, Bases, Canvas, Kanban, Omnisearch, Charts, Excalidraw accents.
- `extras/iconic-preset.json` for matching tab/ribbon iconography.

Built on Cupertino (MIT) — upstream chassis retained.
