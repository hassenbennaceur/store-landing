# LumoStore: Responsive Store Landing Page

## Files
- `index.html`: page structure (header, hero, features, products, newsletter, footer)
- `css/style.css`: custom styles + media queries
- `images/`: SVG product illustrations
- `vendor/`: local copy of Bootstrap 5.3.3 and Bootstrap Icons (works offline)
- `screenshots/`: desktop (1440px), tablet (768px) and mobile (390px) captures

## Design choices
- **Palette:** warm orange accent (#ff6b35) on a deep navy (#2b2d42) with soft cream backgrounds. Orange draws the eye to buttons and prices, navy keeps text readable.
- **Typography:** system font stack for fast loading; bold, large headings and muted grey body text for clear hierarchy.
- **Header:** sticky navbar with anchor links to each section, cart icon with live badge, and a hamburger menu on screens below 992px.
- **Hero:** pure CSS gradient background (no heavy image), a strong headline, and one clear call to action. The hero image is hidden on tablets/phones to keep the message focused.
- **Products:** 4 cards in a Bootstrap grid: 1 column on phones, 2 on tablets, 4 on desktops. Each card has an image, name, description, price and a "Shop Now" button. Cards lift on hover; small tags (Best seller / New / -20%) add interest.
- **Footer:** four columns on desktop that stack on mobile, with contact info and social icons.

## Responsive strategy
- Bootstrap grid (`col-12 col-sm-6 col-lg-3`) handles the layout shifts.
- Custom media queries at 991.98px, 767.98px and 575.98px scale the hero title, spacing, and make the CTA full-width on small phones.
- Tested at 320, 390, 768 and 1440px: no horizontal scrolling.

## Bootstrap features used (extra points)
Grid, sticky navbar with collapse, cards, badges, buttons, form controls, toast notifications (shown when clicking "Shop Now"), utility classes, and Bootstrap Icons.
