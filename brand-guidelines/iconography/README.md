# Iconography documentation and usage guidelines

This guide defines a starting point for a unified AsyncAPI icon system that can be used across marketing surfaces and tooling UIs.

## Goals

- Keep icons visually consistent with the existing AsyncAPI brand mark and tooling logos.
- Prefer simple geometric forms that stay readable at small sizes.
- Make the set usable in both product interfaces and editorial/marketing layouts.

## Core style rules

- Use a `2px` stroke on a `24 x 24` grid.
- Prefer rounded joins and rounded line caps.
- Build icons from circles, straight segments, and soft radii rather than sharp ornamental detail.
- Keep fills optional; default to outline-first icons.
- Avoid mixing multiple stroke weights inside one icon.

## Color usage

- Default UI icon color: `#1B1130`
- Accent / active color: `#19B5FE`
- Inverse icon color on dark surfaces: `#FFFFFF`

Icons should work in monochrome first. Accent fills should only be used to highlight one intentional focus area.

## Categories

- Platform concepts: event, channel, broker, schema
- Product actions: search, generate, validate, inspect
- Ecosystem markers: docs, community, integrations, automation

## Asset structure

- Store reusable source icons in `brand-guidelines/iconography/svg/`
- Keep naming flat and descriptive: `asyncapi-icon_event.svg`
- Export dark and light variants only when a single monochrome source is not sufficient

## Starter set

The initial seed set included here is intentionally small:

- Event
- Channel
- Broker
- Schema

These icons are meant to establish the visual language before expanding the full library.

## Contribution guidance

- New icons should align to the same 24px grid and 2px stroke.
- Reuse the same corner radius language before inventing new silhouettes.
- If an icon needs a filled area to be understandable, keep the fill to one dominant shape.
- Submit SVG exports with clean paths and without editor metadata when possible.

[<-- Back to Brand Guidelines home](/brand-guidelines/README.md)
