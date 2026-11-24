# WanderLust Travel Destination Website Template

A modern, responsive travel destination website built strictly using **HTML and CSS only (Zero JavaScript)**.

Default featured destination: **Bali, Indonesia**, with clean modular placeholders for **[Destination Name]** so you can easily adapt it to any global destination (such as Santorini, Tokyo, Swiss Alps, Hawaii, etc.).

---

## 📁 Project Structure

```text
PROJECT/
├── index.html        # Semantic, accessible HTML5 structure
├── style.css         # Modern pure CSS stylesheet with CSS variables
└── README.md         # Customization guide and instructions
```

---

## ✨ Features Included

1. **Pure CSS Responsive Navigation**:
   - Sticky header with glassmorphism blur effect (`backdrop-filter`).
   - Pure CSS mobile hamburger drawer menu using the accessible checkbox-hack (`#menu-toggle:checked ~ .main-nav`), with animated "hamburger" to "X" transformation.
   - Smooth anchor scrolling (`scroll-behavior: smooth`).

2. **Hero Section**:
   - High-resolution tropical landscape photography with soft readability overlay.
   - Welcoming intro, call-to-action buttons, and a quick-facts glass bar (Best Season, Avg Temperature, Currency, Airport).

3. **Destination Introduction**:
   - Dual-layered photographic showcase with customer rating floating card.
   - Culture, cuisine, and wellness key highlights.

4. **Popular Places to Visit**:
   - 6 responsive cards featuring high-definition photography, destination category tags, star ratings, and activity pills.
   - Featured locations: Tegallalang Rice Terraces, Uluwatu Clifftop Temple, Kelingking Bay, Mount Batur Caldera, Sekumpul Waterfalls, and Seminyak Sunset Beach.

5. **Available Travel Packages**:
   - 3 structured package tiers:
     - *Weekend Island Escape (4 Days / 3 Nights)*
     - *Signature Island Explorer (7 Days / 6 Nights)* - highlighted as **Most Popular**
     - *Luxury Wellness & Romance (10 Days / 9 Nights)*
   - Duration badges, placeholder pricing tags, feature checklists, and booking buttons.

6. **Activities & Experiences**:
   - 6 interactive experience cards: Snorkeling with Manta Rays, Volcano Caldera Trekking, Surfing Lessons, Traditional Cooking Class, Holistic Yoga, and White Water Rafting.

7. **Traveler Testimonials**:
   - Social proof cards with star ratings, quotes, and guest avatars.

8. **Comprehensive Booking Section**:
   - Side-by-side trust perks (Free cancellation up to 48 hrs, Best Price Guarantee, 24/7 Concierge).
   - Form fields:
     - Package / Itinerary selector
     - Date inputs (Arrival & Return)
     - Traveler quantity & Stay style (Villas, Eco Resorts, Beachfront)
     - Full Name, Email, Phone / WhatsApp
     - Special requests textarea
     - Terms & conditions checkbox
     - Reservation CTA with pure CSS `:target` confirmation banner.

9. **Interactive FAQ Accordion**:
   - Native HTML5 `<details>` and `<summary>` elements styled with smooth CSS animated icons.

10. **Newsletter & Destination Guide Banner**:
    - Subscription form for free travel guide downloads.

11. **Site Footer**:
    - Quick navigation links, regional hotspot shortcuts, concierge direct contact details, social links, and copyright text.

---

## 🎨 How to Customize Content & Colors

### 1. Changing the Destination Name
In `index.html`, use your editor's **Find and Replace** (`Ctrl + H`):
- Find: `[Destination Name]` &rarr; Replace with your destination (e.g., `Santorini, Greece` or `Kyoto, Japan`).
- Find: `Bali` &rarr; Replace with your destination name.

### 2. Changing the Color Palette
Open `style.css` and modify the CSS variables in the `:root` block at lines 12–25:

```css
:root {
  /* Change brand colors here */
  --color-primary: #0e7490;         /* Main brand color */
  --color-primary-dark: #155e75;    /* Hover state */
  --color-accent: #f97316;          /* CTA button color */
  --color-secondary: #0f172a;       /* Dark slate text */
}
```

### 3. Replacing Images
All image tags in `index.html` use standard `<img>` tags with Unsplash URLs. Replace any `src` attribute with your own image URLs or local image files (e.g., `src="images/my-photo.jpg"`).

---

## 🚀 How to View the Website
Simply double-click `index.html` to open it in any web browser (Chrome, Edge, Firefox, Safari), or serve it with any local static file server.
