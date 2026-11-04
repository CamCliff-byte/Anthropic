# Proposed addition to the `capyble-brand` skill

The current skill gives colours, fonts and logo rules, but no guidance on layout or composition. Its only web guidance is "Border radius: generous (12–20px)" and "prefer flat with subtle border or background change". With nothing else to go on, Claude applied a rounded, bordered, tinted box to every block, which produced the generic "AI kit" look.

Add the section below to `SKILL.md`, replacing "Creating HTML Artifacts / Web Content". Upload it through claude.ai skill settings; edits made inside a cloud session don't sync back.

---

## Creating HTML artifacts and web pages

### Layout

- Group with space first. Use a border, fill or radius only for something that really is a separate object, such as a product screenshot, a button or a mock-up of a page.
- Never put a card inside a card. Don't build a section as a grid of identical cards unless the items really are interchangeable.
- Use one reading column of about 66 characters. Let images, tables and charts run wider.
- Use at most two or three full-width colour bands per page, each with a purpose. Charcoal works for evidence and openings, periwinkle for a proposal or feature, cream for everything else.

### Type

- Manrope only. Build hierarchy with a clear scale: roughly 14 / 17 / 21 / 28 / 40 / 58px.
- Body text is 17–18px at weight 400. Never use weight 300, never right-align body text, never set text below 14px.
- Don't put all-caps, letter-spaced labels above headings. The heading should say what the section is.
- Don't highlight one word or phrase inside a headline.

### Colour

- Lime (`#d7dc38`) is for actions: primary buttons, ticks, the active state. It isn't decoration.
- Never set lime or periwinkle text on cream or white. They measure about 1.5:1 and 2:1 against white, below WCAG's 4.5:1. Use charcoal text, with the colour as a fill behind it.
- Use the light tints (`#f3f7c8`, `#eeeeff`) sparingly. Tinting every box flattens the page.

### Assets

- Use the real logo, illustrated capys and product screens, never CSS stand-ins. The Drive MCP can't return binary files, so public copies are at `capyble.com/wp-content/uploads/`:
  - Horizontal logo: `2026/10/Capyble_Roundel_Knockout_1024-copy-980x297.png`
  - Roundel: `2026/05/cropped-Asset-132-270x270.png`
  - Capy in a bow tie: `2026/04/Asset-135.png`
  - Capy in a sailor hat: `2026/04/Asset-136.png`
  - Capybility Score screen: `2026/05/image-21.png`
- Use one illustrated capy per page, at a moment that benefits from warmth. Not on every section.

### Before publishing

- Screenshot the page on desktop and phone and critique the design, not just bugs. Remove one decorative element before shipping.
