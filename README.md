# Black Excellence Website Project

## Student Information
- **Student Name:** Langelihle Amahle Ntshangase
- **Student Number:** **[INSERT STUDENT NUMBER BEFORE SUBMISSION]**
- **Module:** WEDE5020
- **Project Part:** Part 2 - Designing the Visuals: CSS Styling and Responsive Design

## Project Overview
Black Excellence is a fictional/academic premium sneaker and streetwear brand based in Durban, KwaZulu-Natal. The website combines African culture, streetwear, craftsmanship and storytelling. Part 1 created the semantic HTML foundation; Part 2 applies the approved street-luxury visual direction and responsive CSS styling.

## Part 1 Feedback
No lecturer feedback or corrections were received for Part 1. The existing page structure and content were therefore retained and visually developed for Part 2.

## Website Goals and Objectives
- Present Black Excellence as a premium and culturally rich sneaker brand.
- Build brand awareness and community around Black Excellence culture.
- Showcase collections and the story behind each sneaker.
- Support customer enquiries and future online shopping journeys.
- Provide a mobile-friendly, accessible and visually consistent experience.

## Part 2 CSS Implementation
Part 2 uses one external stylesheet, `css/styles.css`, linked to every HTML page. The stylesheet demonstrates:

- A global CSS reset and consistent `box-sizing`.
- Base styles for colour, spacing and typography.
- Playfair Display for primary headings, Montserrat for navigation/CTAs, and Open Sans for body copy.
- CSS Grid and Flexbox for page layouts, cards, navigation, forms and footer content.
- The approved Black, Gold (`#D4AF37`), White and Charcoal palette.
- Borders, shadows, gradients and consistent rounded corners for the street-luxury visual system.
- `:hover`, `:focus` and `:active` states for links, buttons, form fields and interactive elements.
- Relative units including `rem`, `%` and `clamp()` for responsive spacing and typography.
- Responsive images using `srcset`, `sizes` and `<picture>` elements for the logo and the original Black Excellence sneaker renders (Madiba 1, Ubuntu High, Heritage Runner and Durban Wave).
- A refined Shop page featuring a hero product showcase, consistent product cards, static concept pricing and cleaner product metadata.

## Responsive Design and Breakpoints
The site follows a desktop-first layout that adapts at the following breakpoints:

| View | Breakpoint / Test Width | Behaviour |
|---|---:|---|
| Desktop | Above 1024px; tested at 1440px | Full multi-column layouts and horizontal primary navigation. |
| Tablet | 1024px and below; tested at 768px | Major grids reduce to two columns or one column; header stacks. |
| Mobile | 720px and below; tested at 390px | Single-column content, smaller type, compact four-column navigation grid, responsive forms and cards. |

## Responsive Screenshot Evidence
Representative screenshot evidence for the responsive layout is stored in `screenshots/` to demonstrate desktop, tablet and mobile presentation.

### Desktop - 1440 × 900
![Desktop homepage](screenshots/desktop-home.png)

### Tablet - 768 × 1024
![Tablet homepage](screenshots/tablet-home.png)

### Mobile - 390 × 844
![Mobile homepage](screenshots/mobile-home.png)

## Sitemap
```text
Home (index.html)
├── Our Story (about.html)
├── Shop (products.html)
├── Collections (collections.html)
├── Community (community.html)
├── Enquiry (enquiry.html)
└── Contact / Support (contact.html)
```

A visual sitemap is available at `images/sitemap.png`.

## File and Folder Structure
```text
BlackExcellence_Part2_Website/
├── index.html
├── about.html
├── products.html
├── collections.html
├── community.html
├── enquiry.html
├── contact.html
├── README.md
├── CHANGELOG.md
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
│   ├── black-excellence-logo.jpeg
│   ├── black-excellence-logo-240.jpg
│   ├── black-excellence-logo-480.jpg
│   ├── black-excellence-logo-960.jpg
│   ├── sitemap.png
│   └── sneakers/
│       ├── madiba-1-{480,800,1200}.jpg
│       ├── ubuntu-high-{480,800,1200}.jpg
│       ├── heritage-runner-{480,800,1200}.jpg
│       └── durban-wave-{480,800,1200}.jpg
└── screenshots/
    ├── desktop-home.png
    ├── tablet-home.png
    └── mobile-home.png
```

## Testing and Iteration
Testing focuses on the requirements stated for Part 2: external CSS linking, Grid/Flexbox layouts, typography and colour styling, pseudo-class states, media queries, relative units, responsive images and internal navigation.

The site was also visually reviewed at desktop, tablet and mobile widths. Multi-column content converts to fewer columns or a single column as space reduces, typography scales with `clamp()`, and navigation is reformatted for narrow screens.

## Changelog
See `CHANGELOG.md` for Part 1 history and new Part 2 CSS/responsive-design entries.

## References
- Black Excellence. 2026. Brand concept, organisation overview and website project content. Unpublished student project material.
- Google Fonts. 2026. *Playfair Display, Montserrat and Open Sans*. Used for the proposed typography system.
- Mozilla Developer Network (MDN). 2026. *CSS Grid Layout, Flexbox, Media Queries and Responsive Images*. Used as technical reference material.
- World Wide Web Consortium (W3C). 2025. *Web Content Accessibility Guidelines (WCAG) 2.1*. Accessibility reference.

## GitHub Notes
Use the private repository created from the lecturer-provided GitHub link. Commit Part 2 changes in logical stages with descriptive commit messages, for example:

1. `style: add external stylesheet and base typography`
2. `style: add desktop grid and flexbox layouts`
3. `style: add responsive tablet and mobile breakpoints`
4. `docs: add Part 2 testing screenshots and changelog`

Before submission, replace the student-number placeholder above and paste the final repository URL into the required submission field.
