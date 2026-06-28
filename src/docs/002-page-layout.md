# Page Layout System

## Overview

The page layout system defines the global spatial structure of the resume.

It establishes how content is positioned on the page, ensuring a consistent and readable layout across all sections.

This system is independent of typography and content structure.

---

## Design Principles

- Structure over decoration
- Consistency over flexibility
- Content-driven layout decisions
- Minimal and predictable spacing rules
- Single-column layout for readability

---

## Page Format

- Paper size: A4
- Layout: Single column
- Orientation: Portrait

---

## Margins

The document must use consistent margins on all sides.

Recommended baseline:

- Top: 1.5–2.0 cm
- Bottom: 1.5–2.0 cm
- Left: 1.8–2.2 cm
- Right: 1.8–2.2 cm

Margins should ensure:
- comfortable reading width
- balanced whitespace
- professional CV density

---

## Content Width

- Content must be centered on the page
- Line length must support readability (no overly wide text blocks)
- No multi-column layout is allowed

---

## Vertical Rhythm

Vertical spacing must be consistent across the document.

Rules:

- All vertical spacing must derive from a base rhythm
- No arbitrary spacing in sections
- Spacing must be consistent between similar elements

---

## Layout Constraints

- Sections must NOT define margins or page geometry
- Layout must not depend on content type
- No manual positioning (e.g. absolute spacing hacks)
- No layout logic inside section files

---

## Separation of Concerns

This system defines:

- page structure
- margins
- global spacing rules

It does NOT define:

- typography (handled in `001-typography.md`)
- semantic styles
- content structure

---

## Guiding Principle

The layout defines structure, not meaning.