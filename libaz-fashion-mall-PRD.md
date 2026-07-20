# 📋 Product Requirements Document (PRD)
## Libaz Fashion Mall — Official Website

---

> **Document Version:** 1.0.0
> **Created:** July 2026
> **Location:** Libaz Fashion Mall, Kadai, Khagra, Berhampore, West Bengal 742101
> **WhatsApp Contact:** +91 94344 41519
> **Logo URL:** https://i.ibb.co/HfRG6KSG/Libaz-logo.png

---

## 📌 Table of Contents

1. [Project Overview](#1-project-overview)
2. [Goals & Objectives](#2-goals--objectives)
3. [Target Audience](#3-target-audience)
4. [Design System](#4-design-system)
5. [Site Architecture & Pages](#5-site-architecture--pages)
6. [Feature List (A to Z)](#6-feature-list-a-to-z)
7. [Asset Inventory (All Image URLs)](#7-asset-inventory-all-image-urls)
8. [Scroll & Animation Behavior](#8-scroll--animation-behavior)
9. [Responsive Design Specs](#9-responsive-design-specs)
10. [Navigation & Header](#10-navigation--header)
11. [Homepage Sections (Detailed)](#11-homepage-sections-detailed)
12. [Contact & WhatsApp Integration](#12-contact--whatsapp-integration)
13. [Gallery & Mall Photos](#13-gallery--mall-photos)
14. [Technical Requirements](#14-technical-requirements)
15. [SEO Requirements](#15-seo-requirements)
16. [Performance Requirements](#16-performance-requirements)
17. [Accessibility Requirements](#17-accessibility-requirements)

---

## 1. Project Overview

**Project Name:** Libaz Fashion Mall — Official Website
**Type:** Premium Shopping Mall Showcase Website
**Theme:** Ultra-modern, Premium Light Theme with 3D visual effects
**Primary City/Location Display Name:** Berhampur *(shown as main city in header/footer)*
**Full Address:** Libaz Fashion Mall, Kadai, Khagra, Berhampore, West Bengal 742101

### Summary
Libaz Fashion Mall er jonno akta full professional, premium, ultra-modern website toiri korte hobe.
Website ta hobe light theme based, kintu ultra vibes er sathe — glassmorphism card, smooth scroll
parallax, 3D effects, micro-animations shob milie akta world-class shopping mall experience.
Website ta fully mobile responsive o desktop responsive hobe. Visitors jano prothom dekhei "wow" feel pabe.

---

## 2. Goals & Objectives

| # | Goal | Priority |
|---|------|----------|
| 1 | Libaz Fashion Mall er brand identity online a establish kora | Critical |
| 2 | Mall er location, contact, o shopping info show kora | Critical |
| 3 | Premium visual experience diye visitors attract kora | Critical |
| 4 | Mobile users der jonno perfectly optimized UX | Critical |
| 5 | WhatsApp er maddome direct customer engagement | High |
| 6 | Google Maps integration diye location show kora | High |
| 7 | Photo gallery diye mall er beauty showcase kora | High |
| 8 | SEO optimize kore Google search e rank kora | Medium |
| 9 | Social media links add kora | Medium |
| 10 | Future e e-commerce ready structure rakha | Low |

---

## 3. Target Audience

- **Primary:** Local shoppers from Berhampore, Berhampur, Murshidabad district
- **Secondary:** Visitors, tourists, nearby city shoppers (Kolkata, Krishnanagar, etc.)
- **Age Group:** 16-55 years
- **Device Usage:** 70% mobile, 30% desktop/tablet
- **Language:** Bengali-speaking, Hindi-speaking, English-reading audience

---

## 4. Design System

### 4.1 Color Palette

```
Primary Brand Color  : #C8963E  (Gold / Warm Amber)
Secondary Color      : #1A1A2E  (Deep Navy — used for text/accents)
Background           : #FAFAF8  (Off-White / Warm White)
Surface Card         : #FFFFFF  (Pure White with shadow)
Glass Surface        : rgba(255, 255, 255, 0.65)
Accent Light         : #F5E6C8  (Warm Cream)
Accent Dark          : #8B6914  (Deep Gold)
Text Primary         : #1C1C1C  (Almost Black)
Text Secondary       : #5A5A5A  (Medium Gray)
Text Muted           : #9A9A9A  (Light Gray)
Success Green        : #2ECC71
WhatsApp Green       : #25D366
Border Color         : rgba(200, 150, 62, 0.2)
Shadow Color         : rgba(200, 150, 62, 0.12)
```

### 4.2 Typography

```
Font Heading  : 'Playfair Display', serif       — for titles, hero text
Font Body     : 'Inter', sans-serif             — for paragraphs, UI
Font Accent   : 'Cormorant Garamond', serif     — for luxury sub-headings
Font Source   : Google Fonts (CDN)
```

### 4.3 Spacing Scale

```
xs   : 4px
sm   : 8px
md   : 16px
lg   : 24px
xl   : 32px
2xl  : 48px
3xl  : 64px
4xl  : 96px
```

### 4.4 Border Radius

```
Small Card  : 12px
Large Card  : 24px
Button      : 50px (pill shape)
Image Frame : 16px
Tag/Badge   : 999px (full round)
```

### 4.5 Shadows

```css
/* Soft card shadow */
box-shadow: 0 4px 24px rgba(200, 150, 62, 0.10);

/* Elevated card shadow */
box-shadow: 0 12px 48px rgba(200, 150, 62, 0.18);

/* Glass card shadow */
box-shadow: 0 8px 32px rgba(31, 38, 135, 0.08);

/* Button shadow */
box-shadow: 0 4px 20px rgba(200, 150, 62, 0.35);
```

### 4.6 Glassmorphism Style

```css
background      : rgba(255, 255, 255, 0.65);
backdrop-filter : blur(12px) saturate(180%);
border          : 1px solid rgba(255, 255, 255, 0.8);
border-radius   : 24px;
```

---

## 5. Site Architecture & Pages

```
libazfashionmall.com/
├── Home (index.html)           — Main landing page (full showcase)
├── About Us (/about)           — Mall history, vision, team
├── Shops & Brands (/shops)     — Store directory / brands list
├── Collections (/collections)  — Featured fashion collections
├── Gallery (/gallery)          — Photo gallery of the mall
├── Visit Us (/visit)           — Location, map, hours
└── Contact (/contact)          — Contact form + WhatsApp
```

---

## 6. Feature List (A to Z)

| # | Feature | Description |
|---|---------|-------------|
| A | Animated Hero Section | Full-screen hero with parallax background, animated text entrance |
| B | Brand Showcase | Grid/carousel of featured brands inside the mall |
| C | Contact Form | Name, email, message form with validation |
| D | Dynamic Scroll Animations | Elements animate in as user scrolls (fade, slide, scale) |
| E | Embedded Google Maps | Interactive map showing exact mall location |
| F | Fixed Sticky Header | Transparent header that becomes solid on scroll |
| G | Gallery Section | Masonry/grid photo gallery with lightbox popup |
| H | Hero Parallax | Background dress/product image scrolls at different speed creating depth |
| I | Image Lazy Loading | Images load only when in viewport for performance |
| J | JavaScript Smooth Scroll | Silky smooth scrolling between sections |
| K | Keyframe Animations | CSS keyframe animations for entrance, hover, pulse effects |
| L | Lightbox Gallery | Click on gallery photo to see full-screen view |
| M | Mobile Navigation | Hamburger menu for mobile, slide-out drawer |
| N | Newsletter Signup | Email subscription input in footer |
| O | Opening Hours Display | Mall timing table shown in Visit section |
| P | Parallax Scroll Effect | Transparent product image (dress/tshirt) moves on scroll |
| Q | Quick Info Bar | Top banner with location, phone, hours |
| R | Responsive Design | Perfect layout on mobile (320px+), tablet (768px+), desktop (1280px+) |
| S | Sticky WhatsApp Button | Floating WhatsApp CTA button always visible on screen |
| T | Testimonials Section | Customer reviews/quotes carousel |
| U | Ultra-modern UI | Premium glassmorphism cards, gold accents, luxury feel |
| V | Video Background (Optional) | Subtle looping video or cinemagraph in hero |
| W | WhatsApp Integration | Click-to-chat via wa.me link (+91 94344 41519) |
| X | Cross-browser Compatible | Works on Chrome, Safari, Firefox, Edge |
| Y | Year Counter / Stats | Animated number counter (years, stores, customers) |
| Z | Zero-layout-shift Images | All images have defined width/height to prevent CLS |

---

## 7. Asset Inventory (All Image URLs)

### 7.1 Logo

| Asset | URL |
|-------|-----|
| Libaz Logo (PNG) | https://i.ibb.co/HfRG6KSG/Libaz-logo.png |

### 7.2 Mall Interior / Exterior Photos

| Asset Name | URL |
|------------|-----|
| Libaz Photo 1 | https://i.ibb.co/nMDbZ4qP/Libaz-photo-1.jpg |
| Libaz Photo 2 | https://i.ibb.co/d4QmqhjY/Libaz-photo-2.png |
| Libaz Photo 3 | https://i.ibb.co/C3Hr3dsQ/Libaz-photo-3.jpg |
| Libaz Photo 4 | https://i.ibb.co/svSHZFxt/Libaz-photo-4.jpg |
| Libaz Photo 5 | https://i.ibb.co/vxGgDcgn/Libaz-photo-5.png |
| Libaz Photo 6 | https://i.ibb.co/tTm3CzpJ/Libaz-photo-6.png |

### 7.3 Mall Face / Exterior Shots

| Asset Name | URL |
|------------|-----|
| Libaz Mall Font Face | https://i.ibb.co/pBNgxnNS/Libaz-mall-font-face.jpg |
| Libaz Face 2 | https://i.ibb.co/C52y0LH9/Libaz-face-2.jpg |

### 7.4 Transparent Product Images (for Parallax)

| Asset Name | URL | Usage |
|------------|-----|-------|
| Women's Dress (transparent BG) | https://pngimg.com/uploads/dress/dress_PNG127.png | Hero parallax layer |
| Boys T-Shirt (transparent BG) | https://images.podos.io/gdlbilqqwzudzx65bduiyt8rt8zoivypdnrnufhndtisjogo.png.png?w=1080&h=auto | Section parallax element |

### 7.5 Usage Map

```
Hero Section         -> Libaz Photo 1 (background) + Dress PNG (parallax overlay)
About Section        -> Libaz Face 2 + Libaz Mall Font Face
Gallery Section      -> All 6 Libaz Photos (Photo 1-6)
Brands/Shop Section  -> T-Shirt PNG (floating 3D product card)
Footer               -> Logo PNG
Favicon              -> Logo PNG (cropped/resized)
```

---

## 8. Scroll & Animation Behavior

### 8.1 Hero Parallax (Most Important!)

```
Element   : Transparent Dress PNG image
Behavior  : As user scrolls DOWN, the dress image moves UP slower than page scroll speed.
            Creates a cinematic 3D depth feeling.
Position  : Absolutely positioned behind hero text, slightly right-aligned
Opacity   : Starts at 0.85, fades to 0 as user scrolls past hero
Transform : translateY(scrollY * 0.4) — 40% of scroll speed
```

JavaScript Implementation:
```javascript
window.addEventListener('scroll', () => {
  const scrollY = window.scrollY;
  const dressImg = document.querySelector('.hero-parallax-dress');
  dressImg.style.transform = `translateY(${scrollY * 0.4}px)`;
  dressImg.style.opacity = Math.max(0, 0.85 - scrollY / 600);
});
```

### 8.2 Scroll-triggered Section Animations

```
Trigger   : IntersectionObserver (when element enters 80% of viewport)
Animation : fadeInUp — opacity 0 to 1, translateY 40px to 0
Duration  : 0.6s ease-out
Stagger   : 0.1s delay between child elements
```

CSS Keyframe:
```css
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(40px); }
  to   { opacity: 1; transform: translateY(0); }
}
```

### 8.3 Header Scroll Behavior

```
Default State       : Transparent background, white logo
After 80px scroll   : Solid white background, colored logo, box-shadow appears
Transition          : all 0.35s cubic-bezier(0.4, 0, 0.2, 1)
```

### 8.4 Floating WhatsApp Button

```
Position  : Fixed, bottom-right (bottom: 24px, right: 24px)
Animation : Pulse ring effect (CSS animation, 2s loop)
Hover     : Scale up 1.1x with shadow
Mobile    : Same position, slightly smaller
```

### 8.5 Number Counter Animation

```
Trigger   : When stats section enters viewport
Elements  : "100+ Brands", "5+ Years", "50,000+ Happy Customers"
Animation : Count up from 0 to target value over 2 seconds
Easing    : easeOutExpo curve
```

### 8.6 Gallery Hover Effect

```
Default  : Image shown normally
Hover    : Scale (1.06x), brightness increase, gold overlay gradient appears
Cursor   : Zoom-in cursor
Click    : Opens lightbox modal with full image
```

### 8.7 Card Hover (3D Tilt Effect)

```
Effect    : Subtle 3D tilt on mouse move (Vanilla JS)
Max Tilt  : 8 degrees
Scale     : 1.03 on hover
Glare     : Subtle white glare overlay moves with cursor
```

---

## 9. Responsive Design Specs

### 9.1 Breakpoints

```
Mobile Small  : 320px - 479px
Mobile        : 480px - 767px
Tablet        : 768px - 1023px
Desktop       : 1024px - 1279px
Large Desktop : 1280px+
```

### 9.2 Layout Behavior per Screen Size

| Section | Mobile | Tablet | Desktop |
|---------|--------|--------|---------|
| Navbar | Hamburger + Logo | Hamburger + Logo | Full horizontal nav |
| Hero | Single column, text top | Split layout | Full split layout |
| Stats | 1 column | 3 column | 3 column |
| About | Stacked | Side by side | Side by side |
| Gallery | 1 col | 2 col | 3 col masonry |
| Brands | 2 col grid | 3 col grid | 4 col grid |
| Contact | Full width form | 2 col | 2 col |
| Footer | Stacked | 2 col | 4 col |

### 9.3 Touch Interactions (Mobile)

```
Swipe    : Gallery carousel supports touch swipe
Tap      : WhatsApp button large enough (min 48px touch target)
Scroll   : Momentum scrolling enabled (-webkit-overflow-scrolling: touch)
```

---

## 10. Navigation & Header

### 10.1 Header Structure

```
[LEFT]   Logo (Libaz Logo PNG) + "LIBAZ FASHION MALL" text
[CENTER] Nav Links (Desktop only):
         Home | About | Shops | Collections | Gallery | Visit Us | Contact
[RIGHT]  WhatsApp CTA Button + Hamburger (mobile)
```

### 10.2 Mobile Drawer Menu

```
Trigger    : Hamburger icon click
Animation  : Slide from right (translateX 100% to 0), 0.35s ease
Overlay    : Dark semi-transparent backdrop
Close      : X button or click outside
Links      : Full-width, large touch targets (56px height)
Bottom     : WhatsApp button + Location info
```

### 10.3 Navigation Links

```
1. Home
2. About Us
3. Shops & Brands
4. Collections
5. Gallery
6. Visit Us
7. Contact
```

---

## 11. Homepage Sections (Detailed)

### Section 1: Top Info Bar
```
Background : Gold (#C8963E)
Text       : White
Content    : Location: Berhampur, West Bengal | Phone: +91 94344 41519 | Open: 10 AM - 9 PM
Behavior   : Hides on mobile scroll down (smooth hide)
```

### Section 2: Hero / Banner
```
Height         : 100vh (full viewport)
Background     : Libaz Photo 1 (dark overlay 40%)
Text (Left)    :
  - Small tag : "Welcome to Berhampur's Finest"
  - H1        : "Libaz Fashion Mall"
  - Sub       : "Where Style Meets Elegance — Kadai, Khagra, Berhampore"
  - CTA Buttons: [Explore Shops] [Visit Us via WhatsApp]
Parallax Layer : Transparent Dress PNG (right side, scrolls at 0.4x speed)
T-shirt PNG    : Floating subtle bottom element
Animation      : Text fades in from bottom on page load (staggered)
```

### Section 3: Stats / Highlights
```
Background : White with subtle gold pattern
3 Cards    :
  - 100+ Brands (animated counter)
  - 5+ Years of Fashion (animated counter)
  - 50,000+ Happy Shoppers (animated counter)
Style      : Glassmorphism cards with gold border
```

### Section 4: About Libaz
```
Layout   : Left (text) | Right (Mall Face Image)
Heading  : "About Libaz Fashion Mall"
Content  :
  - Mall history, vision
  - "Located in the heart of Berhampur..."
  - Location: Kadai, Khagra, Berhampore, West Bengal 742101
  - CTA: [Learn More]
Image    : Libaz-face-2.jpg or Libaz-mall-font-face.jpg
Style    : Image has rounded corners + gold border frame + subtle drop shadow
```

### Section 5: Featured Collections
```
Heading   : "Our Featured Collections"
Sub       : "Explore the latest fashion trends at Libaz"
Cards (4) :
  - Women's Fashion (Dress PNG visual)
  - Men's Wear (T-Shirt PNG visual)
  - Kids' Wear
  - Ethnic & Traditional
Card Style: 3D tilt effect, gradient overlay, hover zoom
```

### Section 6: Mall Gallery (Photo Showcase)
```
Heading  : "Inside Libaz Fashion Mall"
Layout   : Masonry grid
Photos   :
  - https://i.ibb.co/nMDbZ4qP/Libaz-photo-1.jpg
  - https://i.ibb.co/d4QmqhjY/Libaz-photo-2.png
  - https://i.ibb.co/C3Hr3dsQ/Libaz-photo-3.jpg
  - https://i.ibb.co/svSHZFxt/Libaz-photo-4.jpg
  - https://i.ibb.co/vxGgDcgn/Libaz-photo-5.png
  - https://i.ibb.co/tTm3CzpJ/Libaz-photo-6.png
Hover    : scale + gold overlay
Click    : Lightbox fullscreen
Mobile   : Single column scroll, touch-swipe
```

### Section 7: Why Choose Libaz?
```
Heading  : "Why Libaz Fashion Mall?"
Cards (6):
  - Premium Brands
  - Latest Fashion Trends
  - Central Location — Berhampur
  - Best Prices in Murshidabad
  - Ample Parking
  - Safe & Comfortable Shopping
Style    : Icon + title + description, hover lift effect
```

### Section 8: Testimonials
```
Heading   : "What Our Shoppers Say"
Layout    : Horizontal auto-scroll carousel
Cards     : Customer name, location (e.g. "Berhampore"), star rating, quote
Auto-play : Yes, 4s interval
Touch     : Swipe support on mobile
```

### Section 9: Visit Us / Location
```
Heading  : "Find Us in Berhampur"
Left     :
  - Full address display (styled)
  - Opening hours table:
      Mon-Sat : 10:00 AM - 9:00 PM
      Sunday  : 11:00 AM - 8:00 PM
  - Phone / WhatsApp button
Right    :
  - Embedded Google Maps (iframe)
  - Pin on: Libaz Fashion Mall, Kadai, Khagra, Berhampore, West Bengal 742101
```

### Section 10: Contact / WhatsApp CTA Banner
```
Background : Gold gradient (#C8963E to #8B6914)
Text       : White
Content    :
  - "Get in Touch with Libaz Fashion Mall"
  - "Questions? We're just a WhatsApp message away!"
  - Button : [Chat on WhatsApp] -> wa.me/919434441519
  - Button : [Call Us] -> tel:+919434441519
```

### Section 11: Footer
```
Columns (4):
  1. Logo + tagline + social icons
  2. Quick Links (Home, About, Gallery, Contact)
  3. Contact Info (address, phone, WhatsApp)
  4. Newsletter signup (email input + subscribe button)

Bottom bar: 2026 Libaz Fashion Mall. All rights reserved. | Berhampur, West Bengal
```

---

## 12. Contact & WhatsApp Integration

### 12.1 WhatsApp Details

```
Number      : +91 94344 41519
wa.me Link  : https://wa.me/919434441519
Pre-message : ?text=Hello%20Libaz%20Fashion%20Mall!%20I%20am%20interested%20in%20visiting.
```

### 12.2 Floating WhatsApp Button CSS

```css
.whatsapp-float {
  position: fixed;
  bottom: 24px;
  right: 24px;
  width: 60px;
  height: 60px;
  background: #25D366;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 4px 20px rgba(37, 211, 102, 0.5);
  z-index: 9999;
  animation: pulse-whatsapp 2s infinite;
}

@keyframes pulse-whatsapp {
  0%   { box-shadow: 0 0 0 0 rgba(37, 211, 102, 0.6); }
  70%  { box-shadow: 0 0 0 16px rgba(37, 211, 102, 0); }
  100% { box-shadow: 0 0 0 0 rgba(37, 211, 102, 0); }
}
```

### 12.3 Contact Form Fields

```
Name     : Text input (required)
Phone    : Tel input
Email    : Email input
Message  : Textarea (min 100px height)
Submit   : "Send Message" button -> gold gradient style
```

---

## 13. Gallery & Mall Photos

### 13.1 Gallery Grid Layout

```
Desktop  : 3 columns, masonry layout
Tablet   : 2 columns
Mobile   : 1 column scrollable

Alt texts:
  photo-1 : "Libaz Fashion Mall exterior view"
  photo-2 : "Inside Libaz Fashion Mall shopping area"
  photo-3 : "Fashion collections at Libaz Mall"
  photo-4 : "Libaz Mall shopping experience"
  photo-5 : "Libaz Fashion Mall brand display"
  photo-6 : "Libaz Fashion Mall interior"
```

### 13.2 Lightbox Behavior

```
Open       : Click on any gallery image
Overlay    : Dark (rgba(0,0,0,0.92)) full screen
Navigation : Left/Right arrow keys + swipe on mobile
Close      : Escape key or X button
Caption    : Image alt text shown below
Animation  : Fade in/out 0.3s ease
```

### 13.3 Mobile Scroll

```
Gallery  : Touch scroll horizontally in carousel mode
Sections : Native smooth scroll
Momentum : -webkit-overflow-scrolling: touch
```

---

## 14. Technical Requirements

### 14.1 Tech Stack

```
HTML       : HTML5 Semantic markup
CSS        : Vanilla CSS (no frameworks) — custom design system
JavaScript : Vanilla JS (no jQuery) — lightweight and fast
Fonts      : Google Fonts CDN
Icons      : Lucide Icons or Font Awesome 6 (CDN)
Maps       : Google Maps Embed API (iframe)
WhatsApp   : wa.me link (no external SDK needed)
```

### 14.2 File Structure

```
libaz-website/
├── index.html              — Main HTML file
├── css/
│   ├── style.css           — Main stylesheet
│   ├── animations.css      — All keyframe & scroll animations
│   └── responsive.css      — Media queries
├── js/
│   ├── main.js             — Core JS (nav, scroll, counter)
│   ├── gallery.js          — Lightbox & gallery logic
│   └── parallax.js         — Parallax scroll effect
├── assets/
│   └── icons/              — SVG icons (WhatsApp, social, etc.)
└── pages/
    ├── about.html
    ├── gallery.html
    ├── shops.html
    ├── visit.html
    └── contact.html
```

### 14.3 External CDN Dependencies

```html
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&family=Cormorant+Garamond:wght@400;500;600&display=swap" rel="stylesheet">

<!-- Lucide Icons -->
<script src="https://unpkg.com/lucide@latest"></script>

<!-- No jQuery. No Bootstrap. No Tailwind. Pure Vanilla! -->
```

### 14.4 Browser Support

```
Chrome            : 90+
Safari            : 14+
Firefox           : 88+
Edge              : 90+
Samsung Internet  : 12+
```

---

## 15. SEO Requirements

### 15.1 Meta Tags

```html
<title>Libaz Fashion Mall — Premier Shopping Mall in Berhampur, West Bengal</title>

<meta name="description" content="Libaz Fashion Mall — Berhampur's most premium shopping destination. Located at Kadai, Khagra, Berhampore, West Bengal 742101. 100+ brands, latest fashion, best prices.">

<meta name="keywords" content="Libaz Fashion Mall, shopping mall Berhampore, Berhampur mall, Khagra shopping, fashion West Bengal, Murshidabad shopping">

<meta property="og:title" content="Libaz Fashion Mall — Berhampur's Premium Shopping Mall">
<meta property="og:image" content="https://i.ibb.co/pBNgxnNS/Libaz-mall-font-face.jpg">
<meta property="og:type" content="website">
<meta property="og:locale" content="en_IN">
```

### 15.2 Structured Data (JSON-LD)

```json
{
  "@context": "https://schema.org",
  "@type": "ShoppingCenter",
  "name": "Libaz Fashion Mall",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Kadai, Khagra",
    "addressLocality": "Berhampore",
    "addressRegion": "West Bengal",
    "postalCode": "742101",
    "addressCountry": "IN"
  },
  "telephone": "+919434441519",
  "openingHours": ["Mo-Sa 10:00-21:00", "Su 11:00-20:00"],
  "logo": "https://i.ibb.co/HfRG6KSG/Libaz-logo.png",
  "image": "https://i.ibb.co/pBNgxnNS/Libaz-mall-font-face.jpg"
}
```

---

## 16. Performance Requirements

| Metric | Target |
|--------|--------|
| Page Load Time | < 3 seconds on 4G |
| First Contentful Paint (FCP) | < 1.5s |
| Largest Contentful Paint (LCP) | < 2.5s |
| Cumulative Layout Shift (CLS) | < 0.1 |
| Lighthouse Score (Mobile) | > 85 |
| Lighthouse Score (Desktop) | > 90 |

### Optimization Techniques

```
- Lazy load all images below the fold (loading="lazy")
- Preload hero background image (rel="preload")
- Use srcset for responsive images where possible
- Minify CSS & JS for production
- Avoid render-blocking resources
- Use system fonts as fallback
- Defer non-critical JS (defer attribute)
- Preconnect to Google Fonts CDN
```

---

## 17. Accessibility Requirements

```
- All images have descriptive alt text
- Minimum contrast ratio: 4.5:1 (text on background)
- All interactive elements focusable via keyboard
- ARIA labels on icon-only buttons (WhatsApp, close, arrows)
- Skip navigation link at top of page
- Semantic HTML5 elements (nav, main, section, footer, etc.)
- Form inputs have associated label elements
- Lightbox traps focus when open
- Mobile menu closes on Escape key
- Font size minimum: 16px for body text
- Touch targets minimum: 48x48px
```

---

## Quick Reference Summary

```
Mall Name    : Libaz Fashion Mall
City         : Berhampur (display name)
Full Address : Kadai, Khagra, Berhampore, West Bengal 742101
WhatsApp     : +91 94344 41519
wa.me Link   : https://wa.me/919434441519
Logo         : https://i.ibb.co/HfRG6KSG/Libaz-logo.png
Theme        : Premium Light, Gold Accent, Glassmorphism
Fonts        : Playfair Display + Inter + Cormorant Garamond
Primary Color: #C8963E (Gold)
Tech Stack   : HTML5 + Vanilla CSS + Vanilla JS
```

---

*PRD prepared for Libaz Fashion Mall Website Development.*
*Document Version: 1.0.0 | July 2026*
*All image URLs verified and ready for use.*

---

End of Document
