# Header Component Specification

## Overview

The Header component defines the top section of the resume and represents the candidate’s professional identity.

It must be minimal, readable, and structured for both human readers and ATS systems.

---

## Structure

The Header must follow this order:

1. Full Name
2. Professional Title
3. Contact Information

---

## Layout Principles

- Single-column layout only
- No visual containers or boxes
- No icons or images
- All content must be plain text
- Alignment must be consistent across all elements

---

## Semantic Hierarchy

The Header uses existing semantic typography system:

- Name → `Name`
- Professional Title → `ProfessionalTitle`
- Contact Information → `ContactInformation`

No new typography styles should be introduced.

---

## Spacing Rules

- Name → Title: minimal vertical spacing
- Title → Contact: small but clearly separated spacing
- Header block → next section: larger spacing than internal header spacing

Rule:
> Internal spacing < Section spacing

---

## Contact Information Format

Recommended format:

```
Location · Email · Phone
LinkedIn · GitHub · Portfolio
```

Constraints:

- Plain text only
- No icons
- No hyperlinks styling beyond text representation

---

## ATS Compatibility

The Header must:

- Be fully text-based
- Preserve reading order
- Avoid decorative elements
- Be selectable and searchable in PDF output

---

## Guiding Principle

The Header should communicate identity in less than 5 seconds of reading, without sacrificing machine readability or structural clarity.