# Clean Leadership Website — Sample Template

A complete three-page, mobile-friendly HTML/CSS/JavaScript website for presenting a university president, academic administrator, executive or other professional leader.

**Design reference:** the original sample leadership site was organized around the same three pages used at asratatsedeweyn.com. This edition introduces a separate, simplified design: white backgrounds, light-gray sections, deep slate typography and one understated blue accent.

## Open the website

1. Unzip the downloaded folder.
2. Double-click `index.html` to open the Home page in your browser.
3. Use the menu to navigate to **Leadership & Experience** and **Research & Recognition**.

No hosting, installation, command line or JavaScript frameworks are required. External Google Fonts are optional; readable system fonts display if you are offline.

## Folder structure

```
Leadership_Website_Clean/
├── index.html                     Home
├── leadership.html                Leadership & Experience
├── research.html                  Research & Recognition
├── assets/
│   ├── css/style.css              Complete responsive styling
│   ├── js/main.js                  Mobile menu and year update
│   └── images/
│       ├── portrait-placeholder.svg
│       ├── institution-placeholder.svg
│       ├── research-abstract.svg
│       └── favicon.svg
└── previews/
    ├── desktop-index.png
    ├── mobile-index.png
    ├── desktop-leadership.png
    ├── mobile-leadership.png
    ├── desktop-research.png
    ├── mobile-research.png
    ├── desktop-hero.png
    └── mobile-hero.png
```

## Customize for a real leader

1. **Name and title:** Search the three HTML files for `Dr. Eliana Mercer` and `Academic leader & scholar`. Replace in headings, navigation, page titles and footer.
2. **Professional photograph:** Replace `assets/images/portrait-placeholder.svg` with your client's photo and update the image `src` in `index.html` to the new filename. A portrait-oriented photo works best.
3. **Experience and contact:** Update job titles, institutions, dates, biography, email (`hello@example.com`) and external links.
4. **Research and achievements:** Replace illustrative publications, award titles, degrees and figures with verified data.
5. **Colors:** At the beginning of `assets/css/style.css`, change `--ink`, `--blue`, `--blue-hover`, `--blue-soft`, `--surface` and `--border` to match an individual brand.
6. **Preview:** Open each HTML file on a phone and desktop before publishing. Replace the sample labels and the “noindex” directive when converting the demo into a real public profile.

## Design and functionality

- Responsive desktop, tablet and mobile layouts
- Accessible navigation with keyboard support and an Escape-to-close mobile menu
- Semantic headings, meaningful image descriptions and skip-to-content link
- Expandable publications using native HTML `<details>` elements
- No dependencies for navigation or interactivity
- No real personal claims, attribution or endorsement implied

**Important:** The example leader, positions, award titles, publications, dates, statistics and sample email are fictional placeholders. The template is for presentation purposes only; replace details with approved, verified information before publication.
