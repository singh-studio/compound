# Lauren Carruthers — website concept

A design concept for **laurencarruthers.com**, presenting Lauren Carruthers'
existing services, copy and photography as a single modern page.

**Live:** https://singh-studio.github.io/compound/

## About

Lauren Carruthers is a certified nutrition coach and personal trainer in
Auckland with over ten years' experience. This is an unsolicited concept built
by [Singh Studio](https://www.singhstudio.co.nz) to show how her existing
material could be presented. Every word of copy, every price and every
photograph is hers, reproduced from her live site as of August 2026. Nothing was
invented.

The page is labelled as a concept and carries a disclaimer in the footer. All
forms and buttons are inert — nothing is sent, collected or processed.

## Build a plan

The centrepiece is an interactive planner. Her six services become toggles that
price a package live:

- Nested options — weekly check-ins by messenger ($10/wk) or phone call ($30/wk)
- Quantities for personal training sessions and Glute Camp classes
- One-off and recurring totals kept separate: `$188 today · $10 per week`
- Contextual guidance that also declines a sale — selecting both 1-on-1 Coaching
  and Weekly Check-Ins points out that check-ins are already included
- "Send this to Lauren" writes the enquiry and places it in the contact form

A live countdown tracks the next Online Glute Camp — Tuesdays at 5pm, Auckland time.

## Design

Her existing brand, evolved rather than replaced.

- **Colour** — near-black `#0B090C` with a violet bias, her dusty lilac `#CAA6CC`
  and pale blush `#F9DFFF`, deep plum `#7A4784` for depth
- **Type** — Montserrat 900 uppercase for display, Figtree for body
- **Motion** — scroll reveals, card states, and the class countdown

## Technical

A single self-contained `index.html`. Photography is embedded as base64 data
URIs, so the page has no dependencies beyond Google Fonts. No build step, no
framework, no tracking.

```
index.html    the page
assets/       source photography
```
