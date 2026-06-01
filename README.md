# Static-webpage
A pixel-perfect, fully responsive static website for DecodeLabs, a fictional frontend development studio. This project demonstrates professional-grade HTML and CSS architecture using semantic markup, BEM methodology, CSS custom properties, and accessibility best practices.

Live Preview

Open task1_html.html in any modern browser — no build tools or dependencies required.


Project Structure
decodelabs/
├── task1_html.html   # Main HTML file
└── styles.css        # All styles (separated by concern)

Sections
SectionDescriptionHeaderSticky navigation with animated underline hover effectHeroTwo-column grid layout with floating animated shapesServices4-card grid showcasing expertise areasProcess3-step process with visual dividersPortfolioProject cards with SVG placeholder visuals and tech tagsCTAFull-width call-to-action bannerFooterMulti-column footer with contact info and links

Key Concepts Demonstrated
Semantic HTML

Proper heading hierarchy (h1 → h3)
Landmark elements: <header>, <main>, <footer>, <nav>, <aside>
<article> for self-contained content (service cards, project cards)
aria-hidden and aria-label for accessibility

CSS Architecture

BEM naming convention — .block__element--modifier throughout
CSS Custom Properties (Design Tokens) — colors, typography, spacing, shadows, and transitions all defined in :root
DRY principles — shared container classes, reusable button and card components
Separation of concerns — CSS organized into 14 clearly commented sections

Layout

CSS Grid for hero section and portfolio grid
Flexbox for header, nav, process steps, and footer
repeat(auto-fit, minmax()) for responsive grid columns without media queries

Responsive Design

Mobile-first breakpoints at 768px and 480px
Fluid typography using CSS variable overrides in media queries
Stacked layouts on small screens

Accessibility & Performance

prefers-reduced-motion media query disables all animations for users who need it
Print stylesheet included
Focus-visible outlines on all interactive elements
WCAG-considerate color contrast
scroll-behavior: smooth and -webkit-font-smoothing for a polished feel


Technologies Used
Show Image
Show Image

Pure HTML5 & CSS3 — zero frameworks, zero JavaScript, zero dependencies
Inline SVG for logo and portfolio card visuals
CSS animations (@keyframes float, @keyframes pulse)


Design Tokens (from styles.css)
TokenValuePurpose--color-primary#1a4d6dBrand blue--color-accent#5a9e6fBrand green--font-displayGeorgia, serifHeadings--font-bodySystem UI sans-serifBody text--container-max-width1280pxMax layout width--grid-columns12Base grid system

What I Learned / Practiced

Structuring a multi-section webpage using only semantic HTML
Building a scalable design token system with CSS custom properties
Applying BEM for maintainable, conflict-free CSS
Creating smooth animations while respecting prefers-reduced-motion
Writing accessible markup with ARIA attributes
Organizing CSS into logical, documented sections for readability

License
This project is open source and available under the MIT License.
