<p align="center">
  <a href="https://www.w3engineers.com" target="_blank">
    <img src="https://w3engineers.com/wp-content/uploads/2024/06/w3-logo-gray.png" alt="W3 Engineers Ltd." width="180" />
  </a>
</p>

<h1 align="center">🏖️ Sanctuary Cap Cana — Resort Detail Page</h1>

<p align="center">
  A fully responsive, multi-section resort detail page built with pure <strong>HTML & CSS</strong><br/>
  as part of the <strong>W3 Engineers Ltd. Internship Program</strong> assignment.
</p>

<p align="center">
  <a href="https://strong-travesseiro.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge&logo=netlify" alt="Live Demo" />
  </a>
  &nbsp;
  <a href="https://www.w3engineers.com" target="_blank">
    <img src="https://img.shields.io/badge/W3%20Engineers%20Ltd.-Internship%20Project-blue?style=for-the-badge" alt="W3 Engineers" />
  </a>
</p>

---

## 📸 Preview

| Desktop | Tablet | Mobile |
|--------|--------|--------|
| Full layout with image grid & booking card | Stacked layout, hamburger menu | Single column, minimal UI |

---

## 📁 Project Structure

```
project/
├── index.html          # Main HTML file
├── style.css           # All styles including responsive
└── assets/
    ├── logo.png
    ├── footer.jpg
    ├── featured-card-1.jpeg
    └── ...             # Other image assets
```

---

## ✨ Features

### Sections Included
- **Header** — Sticky navbar with logo, 4 nav links, mobile hamburger menu
- **Banner** — Breadcrumb, H1, property highlights, 80/20 image grid + booking card, 8-link section nav
- **About** — 60/40 split layout with description & amenities list
- **Resort Highlights** — Featured grid (landscape card + 3 column cards)
- **All Inclusive Amenities** — 3-column bullet list
- **Booking Banner** — Full-width background image with CTA
- **Activities** — 2-column × 3-row cards with image + description
- **Reviews** — 2-column review cards with avatars
- **Policies** — 3×2 grid of policy cards
- **FAQ** — Interactive accordion
- **Location** — 70/30 split with Google Maps embed + info card
- **Nearby Resorts** — 3-column card grid with sticky map
- **Footer** — Newsletter form, destination links, agent hotline, social icons, currency/region selector

### Responsive Breakpoints
| Breakpoint | Target |
|------------|--------|
| `> 1024px` | Desktop |
| `≤ 1024px` | Tablet |
| `≤ 600px`  | Mobile |

### Responsive Behavior Highlights
- Thumbnail images & booking card **hidden** on tablet/mobile — only main banner image shown
- Hamburger drawer menu on mobile/tablet
- All multi-column grids collapse to 1–2 columns
- Sticky map becomes static and full-width
- Footer links stack gracefully

---

## 🛠️ Built With

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic page structure |
| **CSS3** | Layout, animations, responsive design |
| **CSS Grid & Flexbox** | All layout systems |
| **CSS Custom Properties** | Design tokens (colors, spacing, fonts) |
| **Google Fonts** | Playfair Display + Lato |
| **Font Awesome 7** | Icons |
| **Google Maps Embed** | Location section |

> ⚡ No JavaScript frameworks. No CSS frameworks. Pure HTML & CSS — with minimal vanilla JS only for accordion toggle and mobile menu.

---

## 🎨 Design Tokens

```css
:root {
  --color-primary:   #1a5276;   /* Deep ocean blue */
  --color-accent:    #c9a227;   /* Warm gold */
  --color-text:      #1c1c1e;
  --color-muted:     #6b7280;
  --color-bg:        #c7f1fa61;
  --color-white:     #ffffff;
  --color-border:    #e5e0d8;

  --font-heading: 'Playfair Display', Georgia, serif;
  --font-body:    'Lato', sans-serif;

  --max-width: 1280px;
  --radius:    8px;
}
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Open in browser
cd your-repo-name
open index.html
```

Or simply open `index.html` in any modern browser — no build step required.

---

## 📋 Assignment Context

<p>
  <a href="https://www.w3engineers.com" target="_blank">
    <img src="https://w3engineers.com/wp-content/uploads/2024/06/w3-logo-gray.png" alt="W3 Engineers Ltd." width="140" />
  </a>
</p>

This project was completed as part of the **Frontend Development Internship Assignment** at **[W3 Engineers Ltd.](https://www.w3engineers.com)** — a fast-paced IT solutions provider based in Dhaka, Bangladesh, with over a decade of experience delivering innovative technology solutions worldwide.

**Goal:** Recreate a real-world resort detail page layout based on provided design references (desktop, tablet, and mobile PDFs), implementing all sections with pixel-accurate structure and full responsiveness using only HTML and CSS.

---

## 👤 Author

Developed during the W3 Engineers Ltd. Internship Program  
© 2026 All rights reserved
