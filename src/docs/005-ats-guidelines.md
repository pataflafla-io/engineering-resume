# ATS Compatibility Guidelines

## Overview

This document defines the design principles and validation criteria required to maximize compatibility with modern Applicant Tracking Systems (ATS).

The objective is to produce a resume that is both highly readable by humans and reliably parsed by automated recruitment systems.

---

# Design Principles

- Machine-readable before visually impressive.
- Semantic structure over visual decoration.
- Simplicity over complexity.
- Typography should reinforce hierarchy.
- Every visual decision must preserve accessibility.

---

# Document Structure

The resume should:

- use a single-column layout;
- follow a natural reading order;
- use semantic section titles;
- avoid unnecessary visual complexity.

---

# Typography

The resume should:

- use embedded Unicode fonts;
- avoid decorative fonts;
- maintain a consistent typographic hierarchy.

---

# Layout

The resume should:

- avoid tables for page layout;
- avoid text positioned with absolute coordinates;
- use consistent spacing between sections;
- maintain sufficient white space.

---

# Graphics

The resume should not rely on:

- images containing text;
- logos;
- icons required to understand information;
- decorative graphics.

Images may only be used if they are purely decorative and do not contain essential information.

---

# PDF Requirements

The generated PDF must:

- contain selectable text;
- contain searchable text;
- embed all fonts;
- preserve reading order;
- compile without LaTeX errors.

---

# Validation Checklist

## Document

- [ ] PDF compiles successfully
- [ ] No compilation errors
- [ ] No unexpected warnings

## Accessibility

- [ ] Text is selectable
- [ ] Text is searchable
- [ ] Reading order is correct

## Typography

- [ ] Fonts are embedded
- [ ] Unicode text is preserved
- [ ] Visual hierarchy is consistent

## Layout

- [ ] Single-column layout
- [ ] No tables used for layout
- [ ] Consistent spacing

## Graphics

- [ ] No text inside images
- [ ] No icons required to understand content

---

# Guiding Principle

A resume should be designed for people first, while remaining fully compatible with automated recruitment systems.