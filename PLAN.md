# Portfolio Website Plan (Bootstrap 5)

## File structure
```
portfolio/
├── index.html      Home page
├── about.html      About page
├── resume.html     Resume page
├── project.html    Page the home-page image links to
├── css/style.css   Small custom styles
├── images/         Placeholder images (swap for your own)
└── PLAN.md         This plan
```

## Shared on every page
- Bootstrap 5.3 CSS + JS bundle from the jsDelivr CDN.
- `<meta name="viewport">` so the layout is responsive.
- **Sticky nav bar**: `navbar navbar-expand-md sticky-top` with links to Home, About, Resume.
  It collapses into a hamburger menu below the medium breakpoint.
- Content wrapped in a `.container`.

## Home page (index.html)
| Row | Column classes | Content |
|-----|----------------|---------|
| 1 | `col-12` | `<h1>` with placeholder text |
| 2 | `col-12 col-lg-10` | Image (12 cols below large, 10 at large+), wrapped in `<a href="project.html">` |

## Linked page (project.html)
| Column classes | Behavior |
|----------------|----------|
| `col-md-3 d-none d-md-block` | 3 columns; hidden below medium |
| `col-12 col-md-9` | 9 columns of placeholder text; 12 columns below medium |

## About page (about.html)
| Column classes | Behavior |
|----------------|----------|
| `col-12 col-md-4` | Placeholder image; 4 columns, full width at small and below |
| `col-12 col-md-8` | Placeholder text; 8 columns, full width at small and below |

## Resume page (resume.html)
Placeholder sections (Experience, Education, Skills) to be filled in.

## Bootstrap breakpoints used
- sm ≥ 576px, md ≥ 768px, lg ≥ 992px

## Next steps
1. Replace placeholder text and images in `images/`.
2. Fill in resume details (or link a PDF).
3. Test at phone, tablet, and desktop widths (browser dev tools).
