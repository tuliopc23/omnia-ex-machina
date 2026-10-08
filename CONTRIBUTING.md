# Contributing

Fork → branch → PR. Small, focused changes beat sweeping restyles.

## The one rule that matters

`theme.css` is two layers:

1. **Upstream chassis** — everything above the `OMNIA EX MACHINA — authored layer` banner. It tracks Cupertino. Do not edit it; upstream changes land there wholesale and your edits will be lost.
2. **Authored layer** — everything below that banner. This is where all Omnia work happens.

Only touch the authored layer. If an upstream rule fights you, out-specify it (match its specificity and come later in source order) rather than editing it or reaching for `!important`.

## Plugin integrations

- Passive and class-scoped only: key on the plugin's own DOM classes, never on plugin CSS loading order you can't verify.
- Zero cost when the plugin is absent — no `body.has-plugin` toggles you have to maintain, no JS hooks.
- Don't reintroduce `!important` without a `/* required: … */` comment explaining exactly what it beats (name the competing rule).

## Style Settings

- New options go in the `@settings` YAML block with an `omnia-` prefixed `id`, under the right level-1 heading.
- `class-toggle` / `class-select` values become `body` classes; the CSS lives in the authored layer.
- Keep `default` values faithful to the shipped look.

## Before submitting

- Load the theme in a sandbox vault, flip light/dark, check the surfaces you touched.
- Run the Style Settings panel if you changed `@settings` — invalid YAML silently disables the whole block.
- Zero remote `url(...)` references — the theme must be fully self-contained.
