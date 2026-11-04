# Notes for Claude

This repo holds standalone HTML pages for Capyble (for example `runway-planner/`).

## Visual design for any page or artifact

Cam has rejected pages that look like a generic AI kit. Before building a page:

1. Read the frontend-design guidance (`/mnt/skills/public/frontend-design/SKILL.md` in cloud sessions) and the `capyble-brand` skill.
2. Write a short design plan (colour, type scale, layout) and check it against the list of common AI design patterns below.
3. Screenshot the result and critique the design itself, not just bugs, before publishing.

Avoid by default:

- Identical rounded cards in grids, cards inside cards, a border and tinted fill on every block.
- Small all-caps, letter-spaced labels above headings.
- Pills or chips for every tag, status or estimate.
- Highlighting one word or phrase in a headline.
- Meta strings joined with middle dots (A · B · C), `→` on every link, fake browser chrome.
- Drawing logos or illustrations in CSS when real assets exist.
- Many small sections built the same way and given equal weight.

Prefer:

- One reading column (about 66 characters) with whitespace for grouping. Use hairline rules only where rows need separating.
- Hierarchy from type size and weight. Manrope only, body 17–18px, nothing under 14px.
- At most two or three full-width colour bands, each with a purpose. Keep lime (`#d7dc38`) for actions and ticks; never use lime or periwinkle for text on light backgrounds.
- Real Capyble assets. The Drive MCP can't return binary files, so pull the logo, illustrated capys and product screens from `capyble.com/wp-content/uploads/`.
- Real tables and charts for comparisons.
- Fewer, stronger sections. Cut anything that repeats.

See `docs/capyble-brand-web-layout.md` for the proposed addition to the `capyble-brand` skill.
