# Experience Component

## Overview

The Experience component defines how professional work history is structured and presented in the CV.

It is a reusable content unit that can be instantiated multiple times, once per professional experience.

This component is independent of implementation details and focuses only on structure, hierarchy, and information grouping.

---

## Component Structure

Each experience entry is composed of the following elements:

- Company Name
- Job Title / Role
- Time Period
- Location (optional)
- Description
- Technologies Used

---

## Information Hierarchy

The information must be ordered with the following priority:

1. Company Name (highest level of identity)
2. Job Title / Role
3. Time Period
4. Description (responsibilities and achievements)
5. Technologies (stack used)

This hierarchy ensures fast scanning and readability.

---

## Multiple Experiences

The component must support multiple entries with a consistent structure.

Rules:

- Each experience follows the same layout pattern
- Separation between experiences must be visually consistent (handled by layout system, not this component)
- No variation in structure between entries is allowed

---

## Description Guidelines

The description section should:

- Be concise but informative
- Focus on responsibilities and impact
- Avoid repetition of job title
- Be written in plain text (no styling rules defined here)

---

## Technologies Section

Technologies should:

- Be a compact list of tools, frameworks, or languages
- Be secondary to the description
- Not dominate visual hierarchy

---

## Out of Scope

This component does NOT define:

- Typography (handled in `001-typography.md`)
- Page layout or spacing rules (handled in `002-page-layout.md`)
- Visual styling or LaTeX implementation
- Section ordering in the CV

---

## Guiding Principle

The Experience component defines structure, not presentation.