---
name: build-portfolio-website
description: Designs, develops, reviews, and improves the professional portfolio website for Nawanan Khaunsamakhom, positioned as an Interactive Experience Designer specializing in Game Design, UX/UI, and Visual Systems. Use for portfolio structure, visual design, responsive frontend development, project case studies, accessibility, performance, testing, and deployment preparation.
---

# Portfolio Website Skill

## 1. Frontmatter

```yaml
---
name: build-portfolio-website
description: Designs, develops, reviews, and improves the professional portfolio website for Nawanan Khaunsamakhom, positioned as an Interactive Experience Designer specializing in Game Design, UX/UI, and Visual Systems. Use for portfolio structure, visual design, responsive frontend development, project case studies, accessibility, performance, testing, and deployment preparation.
---
```

## 2. Project identity

```markdown
# Portfolio Website

Build and maintain the professional portfolio website for:

- Name: Nawanan Khaunsamakhom
- Positioning: Interactive Experience Designer
- Disciplines: Game Design · UX/UI · Visual Systems
- Primary language: English
- Audience: Recruiters, design teams, game studios, and competition judges
```

## 3. Identity Rules

```markdown
## Identity Rules

Use the exact name “Nawanan Khaunsamakhom” consistently in:

- Page title
- Navigation
- Hero section
- Metadata
- Open Graph metadata
- Structured data
- Image alt text
- CV and contact sections
- Footer
- Download labels
- Generated filenames

Never use alternative English spellings.

Present the portfolio as one coherent professional identity. Do not divide the owner into multiple unrelated career identities.
```

## 4. Website Objective

```markdown
## Website Objective

Design the website to help visitors understand within the first 10 seconds:

1. Who Nawanan is
2. What kind of designer she is
3. What problems she can solve
4. Which projects demonstrate those abilities
5. How to contact or hire her

Prioritize portfolio evidence and case studies over a long CV-style biography.
```

## 5. Information Architecture

```markdown
## Required Information Architecture

Use this content order unless the existing content justifies an adjustment:

1. Navigation
2. Hero and professional positioning
3. Selected Work
4. Project Case Studies
5. Capabilities
6. Design Process
7. About
8. Experience and Education
9. Contact
10. Footer

Do not include the AOT Iceberg project unless explicitly requested.
```

## 6. Case‑Study Structure

```markdown
## Case Study Structure

Present every major project using:

1. Project overview
2. Problem or opportunity
3. Role and responsibilities
4. Target users
5. Constraints
6. Research or discovery
7. Design decisions
8. Interaction or system design
9. Tools and implementation
10. Outcome
11. Reflection and lessons learned

Clearly distinguish individual contributions from team contributions.

Do not invent metrics, clients, responsibilities, research findings, or project outcomes. Mark missing information for user confirmation.
```

## 7. Visual Direction

```markdown
## Visual Direction

Create a professional, contemporary, interactive design with:

- Strong typography and hierarchy
- Editorial portfolio layout
- Intentional whitespace
- Clear grid and alignment
- Restrained color palette
- High‑quality project imagery
- Subtle interaction feedback
- Purposeful transitions
- Visual‑system consistency

The design should feel crafted by an Interactive Experience Designer, not generated from a generic portfolio template.
```

## 8. Visual Restrictions

```markdown
## Visual Restrictions

Avoid:

- Emoji as interface decoration
- Excessive gradients
- Glassmorphism on every component
- Unnecessary rounded cards
- Floating boxes around all content
- Excessive animation
- Decorative effects that reduce readability
- Skill percentage bars
- Generic technology‑logo clouds
- Fake testimonials
- Generic AI‑generated marketing language
- Repetitive card‑grid layouts
- CV‑style walls of text
```

## 9. Interaction Design

```markdown
## Interaction Design

Every interaction must serve navigation, comprehension, or project storytelling.

Use:

- Clear hover and focus states
- Meaningful project previews
- Smooth but restrained transitions
- Keyboard‑accessible navigation
- Reduced‑motion support
- Visible active navigation states
- Clear external‑link and download behavior

Do not add animation solely to make the page feel busy.
```

## 10. Responsive Requirements

```markdown
## Responsive Requirements

Design mobile‑first and verify at:

- 360 px
- 768 px
- 1024 px
- 1440 px

Prevent:

- Horizontal overflow
- Clipped text
- Tiny tap targets
- Unreadable project descriptions
- Broken image crops
- Navigation overlap
- Excessively large hero sections on mobile
```

## 11. Accessibility

```markdown
## Accessibility

Meet practical WCAG 2.2 AA expectations:

- Use semantic HTML
- Maintain sufficient color contrast
- Provide meaningful alt text
- Preserve keyboard navigation
- Show visible focus states
- Label controls correctly
- Respect prefers‑reduced‑motion
- Use headings in logical order
- Do not communicate meaning through color alone
```

## 12. Metadata and Discoverability

```markdown
## Metadata and Discoverability

Include:

- Descriptive page title
- Meta description
- Canonical URL when available
- Open Graph metadata
- Social preview image metadata
- Person structured data
- Meaningful page headings
- Correct favicon references
- Sitemap and robots configuration when appropriate
```

## 13. Development Workflow

```markdown
## Development Workflow

For every implementation task:

1. Inspect the existing project before editing.
2. Identify the current framework and conventions.
3. Preserve working content and user‑authored changes.
4. Create a concise implementation plan.
5. Implement the smallest coherent change.
6. Run formatting, linting, tests, and builds when available.
7. Inspect the result at mobile and desktop sizes.
8. Check keyboard interaction and accessibility.
9. Review the final diff.
10. Report completed work and remaining limitations.

Do not replace the entire project unless the existing architecture makes incremental improvement impractical.
```

## 14. Agent Collaboration

```markdown
## Agent Collaboration

When Codex MCP is available:

- Use the main Antigravity agent for requirements analysis, architecture, UX direction, and final review.
- Delegate bounded implementation and debugging tasks to Codex.
- Give Codex exact target files, requirements, restrictions, and verification criteria.
- Do not let multiple agents edit the same files simultaneously.
- Review all Codex changes before accepting them.
- Run the final test and build from the main agent.
```

## 15. Definition of Done

```markdown
## Definition of Done

A task is complete only when:

- The requested behavior works
- The correct identity is used everywhere
- Existing functionality is not broken
- Layout works across required viewport sizes
- Keyboard and focus behavior work
- No placeholder content remains unintentionally
- No invented claims or metrics were added
- Tests and builds pass when available
- The final result has been visually inspected
```

### File Organization

```text
build-portfolio-website/
├── SKILL.md
├── references/
│   ├── identity-and-content.md
│   ├── case-studies.md
│   └── design-system.md
└── assets/
    ├── logos/
    ├── project-images/
    └── cv/
```

*This SKILL.md provides the standards and reusable guidelines for any portfolio‑building task. Specific content, images, and case‑study details should be kept in the `references/` and `assets/` folders to keep the skill lightweight and context‑efficient.*

