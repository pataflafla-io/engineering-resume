# Typography System

## Overview

The typography system establishes a consistent visual hierarchy across the resume while keeping the document clean, readable, and easy to maintain.

All typography in the project must be applied through semantic styles.

Direct references to font sizes, weights or spacing inside document sections are prohibited.

## Design Principles

* Readability over decoration.
* Consistency over customization.
* Semantic styles over explicit formatting.
* Minimal font weights.
* Visual hierarchy through size, spacing, and weight rather than color.

## Font Family

**Inter**

Chosen for its excellent readability, modern appearance, and widespread adoption in digital products.

## Font Weights

| Weight   | Usage                                               |
| -------- | --------------------------------------------------- |
| Bold     | Primary heading (name)                              |
| SemiBold | Section titles, company names, job titles           |
| Regular  | Body text, dates, technologies, contact information |

No Light, Thin, ExtraBold or Black variants should be used.

## Typography Scale

| Semantic Style      |  Size | Weight   |
| ------------------- | ----: | -------- |
| Name                | 22 pt | Bold     |
| Professional Title  | 11 pt | SemiBold |
| Contact Information |  9 pt | Regular  |
| Section Title       | 12 pt | SemiBold |
| Company Name        | 11 pt | SemiBold |
| Job Title           | 10 pt | SemiBold |
| Date                |  9 pt | Regular  |
| Body                | 10 pt | Regular  |
| Technologies        |  9 pt | Regular  |

## Line Height

| Style        | Line Height |
| ------------ | ----------: |
| Name         |       24 pt |
| Body         |       14 pt |
| Technologies |       12 pt |

## Vertical Spacing

| Element                          | Spacing |
| -------------------------------- | ------- |
| Between paragraphs               | 0.5 em  |
| Before section                   | 1.2 em  |
| After section title              | 0.6 em  |
| Between bullet points            | 0.2 em  |
| Between professional experiences | 1.0 em  |

## Color Palette

Primary

* #202124

Secondary

* #5F6368

Color should reinforce hierarchy, never replace it.

## Semantic Styles

The document should never reference font sizes directly.

Instead, semantic styles should be used throughout the project.

Examples include:

* Name
* ProfessionalTitle
* SectionTitle
* CompanyName
* JobTitle
* Date
* Body
* Technologies

## Guiding Principle

Typography should communicate structure, not decoration.

## Future Implementation

The typography system will be implemented in:

components/typography.tex

using semantic commands such as:

- \NameText
- \ProfessionalTitle
- \SectionTitle
- \CompanyName
- \JobTitle
- \BodyText
- \TechnologiesText