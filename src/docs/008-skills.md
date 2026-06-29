# Skills Component

## Objective

Provide a reusable component for presenting technical skills in a clear, organized, and ATS-friendly format.

The component should integrate with the existing typography and layout systems while maintaining a clean visual hierarchy.

---

## Responsibilities

The Skills component is responsible for:

- Displaying a skill category.
- Displaying the skills belonging to that category.
- Maintaining consistent spacing between categories.
- Remaining independent of page layout concerns.

---

## Public Interface

```latex
\SkillsEntry{<Category>}{<Skills>}
```

### Parameters

| Parameter | Description |
|----------|-------------|
| `#1` | Skill category (e.g. Languages, Backend, Cloud) |
| `#2` | List of skills belonging to the category |

---

## Composition

The component is composed of:

- Category
- Skill list
- Bottom spacing

The component delegates typography to the semantic typography system.

---

## Dependencies

- `components/typography`

---

## Layout

Each entry should be rendered as:

```text
Category
Skill 1 · Skill 2 · Skill 3
```

A consistent vertical spacing should separate consecutive entries.

The component should not introduce page layout logic.

---

## Example Usage

```latex
\SkillsEntry
  {Backend}
  {Go · Java · Node.js}

\SkillsEntry
  {Frontend}
  {React · TypeScript}

\SkillsEntry
  {Cloud}
  {AWS · Docker · Kubernetes}
```

---

## Design Principles

- Reusable
- Semantic
- ATS-friendly
- Minimal
- Consistent with the existing design system

---

## Acceptance Criteria

- Component purpose is defined.
- Public interface is documented.
- Component composition is described.
- Dependencies are identified.
- Example usage is provided.
- Ready for implementation.