# Agency Deliverable Templates: Free Edition

A stylesheet and a starter template for client reports that look like they came from one studio.

No build step, no framework, no dependencies. Open the file in a browser and it works.

## What is inside

```
styles/deliverable.css            one stylesheet: design tokens, 8 category accents, 30+ components, print rules
templates/blank.html              header, executive summary, one section
examples/component-gallery.html   every component with its class names
```

## Quick start

1. Copy `styles/` and `templates/blank.html` into your project. Keep the template one folder below `styles/`, or edit its `<link>` so it points at `deliverable.css`.
2. Open `examples/component-gallery.html` in a browser to see every component.
3. Fill in the bracketed fields in the template and delete the components you do not need.
4. Pick a category. Change the badge text and the two accent lines together:

```html
<span class="header-badge">Strategy</span>
...
:root {
    --accent: var(--color-strategy);
    --accent-bg: var(--color-strategy-bg);
}
```

The eight categories are Strategy, Creative, Performance Marketing, Web Development, AI Solutions, Sales, Operations and Engineering.

5. To make a PDF, open the file in a browser and print to PDF.

## Make it yours

Everything brand-specific sits in the first block of `deliverable.css`:

- `--brand`, `--brand-light`, `--brand-dark`: your brand color.
- `--font`: the font stack. The stylesheet loads DM Sans from Google Fonts. Replace the `@import` line to use another font.
- The eight category colors, the neutrals, and the radius and shadow values.

Keep the token names the same so every template keeps working.

## Paid editions

**Agency Deliverable Templates ($29)** adds five more templates (general report, scored audit, strategy brief, monthly performance report, proposal) and two filled examples: a website audit and a monthly report.

**Agency Deliverable Engine, Full Engine ($89)** adds four Claude Code skills that scaffold a document, write it from your notes under house rules, run 30 automated checks, fix what fails, and package one file you can email. The checker also runs on its own in CI.

Both editions: https://orumani.gumroad.com

## License

MIT. See `LICENSE.md`.
