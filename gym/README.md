# BEAST Fitness Hub — Premium Boutique Gym Website

A modern, high-performance, multi-page static website designed and built for **BEAST Fitness Hub**, a premium boutique gym based in Bangalore.

Built with pure vanilla HTML5, CSS3, and JavaScript — no external frameworks, zero dependencies, lightning-fast load times, and mobile-first responsiveness.

---

## 📸 Preview & Brand Concept

- **Brand Personality**: Confident, athletic, disciplined, premium boutique.
- **Palette**: Deep Charcoal (`#141416` / `#1C1C1F`), Clean Off-White (`#F6F4F1`), and High-Energy Red (`#E10600`).
- **Typography**: Display headlines in `Barlow Condensed`, motivational accents in `Cormorant Garamond` serif italic, and body in `Plus Jakarta Sans`.

---

## 🚀 Pages Included

1. **`index.html` (Home Page)**
   - Sticky glassmorphism navigation with mobile menu drawer.
   - High-impact hero section with vivid backdrop and dual CTAs.
   - Value strip & "Discipline over Motivation" philosophy section.
   - Training & capabilities grid (Strength, Cardio, Coaching, HIIT, Nutrition, Facilities).
   - **Membership Pricing Section**:
     - **1 Month**: ₹1,500
     - **3 Months (Quarterly)**: ₹3,000 (*Best Value* — ₹1,000/mo)
     - **12 Months (Yearly)**: ₹10,000 (*Most Popular* — ~₹833/mo)
     - **Couple Annual Pass**: ₹5,000 yearly (wide dedicated banner)
   - Interactive photo gallery with full-screen lightbox.
   - Motivational quote band.
   - Google Maps embed (Coordinates: `12.6491859, 77.4384088`) and contact info.
   - Final call-to-action & structured footer.

2. **`gallery.html` (Facility Gallery)**
   - Dedicated photo gallery showcase using real gym floor photos.
   - Interactive modal lightbox with keyboard controls (Arrow keys, Escape) and touch support.

3. **`contact.html` (Contact & Location)**
   - Detailed address, phone, email, and daily opening hours breakdown.
   - Embedded Google Map with direct "Get Directions" trigger.
   - Quick action buttons (WhatsApp, Call, Directions).

4. **`book.html` (Book Your Slot / Free Trial Pass)**
   - Complimentary workout session reservation form.
   - Date picker with automatic today's date minimum constraint.
   - Automatic WhatsApp redirection containing pre-formatted booking details.

---

## 🛠️ Key Features

- ⚡ **Zero Dependencies**: Plain HTML/CSS/JS with zero build steps or npm installations needed.
- 📱 **Mobile-First & Touch Ready**: Floating WhatsApp button, fixed bottom action bar on mobile devices, and touch-friendly gallery.
- 🎨 **Custom SVG Logo System**: Sharply vectorized geometric beast mark and stacked wordmark, optimized for favicons, headers, and footers.
- 🔍 **SEO & Structured Data**: Built-in Open Graph metadata and `HealthClub` LocalBusiness JSON-LD schema with exact geo-coordinates.
- ♿ **Accessibility & Performance**: WCAG AA color contrast, keyboard-accessible modals, and support for `prefers-reduced-motion`.

---

## 📂 Project Structure

```
├── index.html          # Main landing page
├── gallery.html        # Facility photo gallery & lightbox
├── contact.html        # Contact, opening hours & Google Maps
├── book.html           # Free trial pass booking form
├── README.md           # Documentation
└── imgs/               # Real facility photography
    ├── WhatsApp Image 2026-10-05 at 12.35.42 AM.jpeg
    ├── WhatsApp Image 2026-10-05 at 12.35.43 AM.jpeg
    ├── WhatsApp Image 2026-10-05 at 12.35.43 AM (1).jpeg
    ├── WhatsApp Image 2026-10-05 at 12.35.43 AM (2).jpeg
    └── WhatsApp Image 2026-10-05 at 12.35.43 AM (3).jpeg
```

---

## ⚙️ Quick Start

### 1. Run Locally
Simply open `index.html` in any modern web browser, or launch a lightweight local server:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```

### 2. Deploy
This project can be deployed instantly on:
- **GitHub Pages**: Push to GitHub and enable Pages in repository settings.
- **Vercel**: Run `vercel` in the root folder or import from GitHub.
- **Netlify**: Drag and drop the folder into the Netlify dashboard.

---

## 📋 Configuration & Placeholders

Search and replace the following placeholders across the HTML files before deploying to production:

| Placeholder | Description | Example |
|---|---|---|
| `[PHONE]` | WhatsApp & telephone number (with country code) | `919876543210` |
| `[OPEN_TIME]` | Gym opening time | `6:00 AM` |
| `[CLOSE_TIME]` | Gym closing time | `10:00 PM` |
| `[PLACEHOLDER: Full address]` | Street address of the gym | `No. 42, Kanakapura Main Rd...` |
| `[CONTACT_EMAIL]` | Gym customer support email | `contact@beastfitnesshub.com` |
| `[INSTAGRAM]` | Instagram profile link | `https://instagram.com/beastfitnesshub` |
| `[FACEBOOK]` | Facebook page link | `https://facebook.com/beastfitnesshub` |

---

## 📄 License

© 2026 BEAST Fitness Hub. All rights reserved.
