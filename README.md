# digitalestateplanning.ai Website

A static HTML/CSS website for digital estate planning education.

## Structure

```
digitalestateplanning-site/
├── index.html          # Home page
├── guide.html          # Step-by-Step Guide (5 steps)
├── inventory.html      # Comprehensive asset checklist
├── platforms.html      # Platform legacy feature guides
├── new-risks.html      # Passkeys, AI, IoT, scams, RUFADAA
├── downloads.html      # Free download page
├── services.html       # Workshops & Workbook
├── css/
│   └── styles.css      # All styles with CSS variables
└── assets/
    ├── checklist.pdf           # (to be created)
    ├── inventory-template.pdf  # (to be created)
    ├── inventory-template.csv  # (to be created)
    └── emergency-card.pdf      # (to be created)
```

## Theming

All colors, fonts, and spacing are controlled by CSS variables in `css/styles.css`.

To change the theme, edit the `:root` section at the top of `styles.css`:

```css
:root {
  --color-primary: #2563eb;        /* Change this for main brand color */
  --color-secondary: #059669;      /* Change this for accent color */
  --font-body: system-ui, ...;     /* Change for different font */
  --font-size-base: 1.125rem;      /* 18px - senior-friendly default */
  /* ... etc */
}
```

## Deployment

This is a static site. Upload all files to your web host or serve with any static file server.

## Notes

- All pages use semantic HTML and are screen-reader friendly
- Print styles are included for checklists and guides
- Responsive design works on mobile, tablet, and desktop
- No JavaScript required for core functionality
