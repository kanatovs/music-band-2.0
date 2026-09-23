# Assignment 2 - Flexbox & Grid checklist

## Task 1 - Navigation Bar
- `#main-header` is placed in the Grid header area.
- `.header-inner` uses `display: flex`.
- Logo is on the left, navigation links are on the right.
- `align-items: center`, `justify-content: space-between`, and `gap` provide alignment and spacing.

## Task 2 - Card Row
- `index.html` contains 3 `.release-card` elements.
- `.card-row` uses Flexbox.
- Cards use `align-items: stretch` and flex column layout for equal heights.
- Cards include image, title, text, and button.
- Hover lifts each card and adds a shadow.

## Task 3 - Grid Areas
- `body` is the parent CSS Grid container.
- Grid areas: `header`, `sidebar`, `main`, and `footer`.
- Desktop: sidebar left, main content right.
- Mobile: areas stack vertically.

## Task 4 - Image Gallery
- `index.html` includes 9 gallery figures.
- `.gallery-grid` uses CSS Grid with equal-width columns.
- Consistent `gap` is applied.
- Captions slide in on hover.

## Responsiveness
- Breakpoints: 1100px, 980px, 760px, and 520px.
- Navigation wraps on small screens.
- Cards, gallery, forms, tour rows, and main Grid layout adapt to mobile widths.

## Review against Web Assignment 2.pdf (2026-09-23)

- Navigation (10%): Flexbox logo/links, alignment and gaps exist on all four pages.
- Cards (10%): three cards have images, titles, descriptions and link-buttons; equal desktop heights and hover effects are implemented.
- Grid layout (10%): named header/sidebar/main/footer areas exist on all pages. Fixed the sidebar's viewport-dependent padding consuming its fixed-width column; the outer gutter is now included in the column width.
- Gallery (10%): nine image elements, equal grid tracks, gaps and hover captions exist. Updated with nine distinct Cold Carti release covers downloaded from Apple Music. Files and source metadata are stored in `assets/covers/`; all nine SHA-256 hashes differ. Square cells preserve complete cover compositions; captions include release titles and years, and covers link to their matching releases.
- UX (10%): adjusted desktop spacing, hero proportions, heading sizing and intermediate-width layouts. The contact form is a static mockup (`action="#"`), not a working message/subscription service. A backend is not explicitly required by this CSS assignment.
- Defense (40%): assessed in person; cannot be verified from project files.
- Report (10%): no submission report PDF was found in this folder. It must include the objective, team name, member names, group, each task's steps and screenshots, reflection and deployed URL.
- Submission: no ZIP or deployment URL was found here, and this folder has no `.git` directory. Repository push, deployment, submission by each member and the LMS deadline cannot be confirmed. The PDF's publishing/submission instructions were treated as assessment criteria, not authorization to publish or submit.

## Layout verification

- Checked all four pages in Chromium/Edge at viewport widths 320, 390, 520, 760, 820, 980, 1100, 1280, 1536, 1920 and 2560 CSS pixels, without browser zoom overrides.
- No horizontal document overflow or broken images at those widths.
- Desktop and mobile home-page screenshots visually reviewed; desktop card heights, gallery caption hover, card lift and local links checked.
- These checks establish layout behavior, not a guaranteed assignment grade.
