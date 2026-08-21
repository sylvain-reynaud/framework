← [aidd-framework](../../README.md)

# aidd-ui 🚧 alpha

Experience design concern for the AI-Driven Development framework: what the user must see first, how a flow should feel, and which motivation loop keeps them coming back. The skills reproduce the judgment of a UX designer, a product-delight expert, and a game designer as reusable expert lenses, so a team without design skills can still ship a product that feels premium.

> Status: alpha (experimental). The plugin is registered with `recommended: false` and stays off the curated install path until it has been dogfooded. Skills and artifacts may change without notice.

Install from the marketplace, or test it from a local checkout:

```
claude --plugin-dir plugins/aidd-ui          # zero-marketplace, session-scoped
# or, persistent:
/plugin marketplace add .                      # register this checkout as a local marketplace
/plugin install aidd-ui@aidd-framework
```

## Journey

1. Describe who the product serves with the persona capability of the product management plugin, once per user segment. The skills below read `aidd_docs/product/personas/*.md` and fall back to one labelled assumed persona when none exists.
2. `03-engagement-system`, once per product: the core loop, the mechanics, the celebration tiers, the guardrails, persisted in `aidd_docs/product/engagement.md`.
3. `01-experience-audit` on a running screen, flow, or the whole app: the ranked premium gaps, each tied to a persona and to evidence, persisted in the dated task folder.
4. `02-experience-design` on a spec or story, before the plan: the experience brief the plan capability consumes. Wireframes stay with planning; visual craft stays with any installed frontend craft capability.

The plugin writes artifacts only. It never edits application source.

## Skills

| Bracket ID | Skill | Description |
| ---------- | ----- | ----------- |
| [7.1] | [experience-audit](skills/01-experience-audit/SKILL.md) | Audit an existing interface through UX, UI, delight, and game-design lenses and the product personas, ranking the gaps that keep it from feeling premium. |
| [7.2] | [experience-design](skills/02-experience-design/SKILL.md) | Produce the experience brief of a feature before it is planned: what each persona must see first, the flow and states, the moment worth remembering. |
| [7.3] | [engagement-system](skills/03-engagement-system/SKILL.md) | Design the product's motivation and gamification system, from core loop to celebrations, with ethical guardrails. |
