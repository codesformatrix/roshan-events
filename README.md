# Roshan Events — Premium Wedding & Event Planner Website

## Project Overview
A production-ready, single-page website for **Roshan Events** — Jaipur's most trusted wedding and event management company. Built as a premium agency-quality site with real event photography in the gallery section.

## 🎯 Client Details
- **Business**: Roshan Events
- **Location**: Durgapura, Jaipur, Rajasthan
- **Phone**: 095878 08416
- **Instagram**: @roshan_events24
- **Google Rating**: 4.8 ★ (80 reviews)
- **Availability**: 24 hours

## ✅ Completed Features

### Sections (8 total)
1. **Hero** — Full-viewport with canvas particle system (floating gold petals), GSAP staggered word reveal, Hindi tagline, Google rating badge, and dual CTA buttons
2. **Stats Bar** — Frosted glass bar with animated count-up counters (500+ events, 4.8 rating, 200+ families, 5+ years)
3. **About / Who We Are** — Two-column layout with rich copy and CSS mandala ornament with "रोशन" center text
4. **Services** — 6 service cards in responsive grid with custom SVG icons and hover animations
5. **Testimonials** — Carousel with 5 real/plausible reviews, auto-advance, touch swipe support, Google branding
6. **Process Timeline** — 4-step horizontal timeline with SVG line-draw animation
7. **Gallery / Our Work** — Asymmetric masonry grid with 7 real event photos, category filtering, full-screen lightbox with keyboard/swipe navigation
8. **Contact & Footer** — Haveli arch decoration, 3-column contact cards, 4-column rich footer with brand, quick links, services, contact info & business hours, social media links

### Gallery Section Details
- **7 real event photographs** from the portfolio:
  - Modern Elegance (Wedding Stage) — Black/white chevron floor, floral iron arch, lavender sofa
  - Grand Ballroom (Reception) — Massive floral chandelier, concentric LED ceiling (wide card)
  - Garden Night (Outdoor Event) — Blue ambient, acrylic tables, hanging lanterns (wide card)
  - Starlight Wedding (Grand Outdoor) — Thousands of fairy lights, Mughal pavilions
  - Royal Jaipur Night (Traditional) — Gold Mughal arches, Edison bulbs, red table linens
  - The Purple Dream (Reception Entry) — Purple tulle clouds, crystal chains, neon panels
  - Garden Mandap (Wedding Ceremony) — Hanging greenery, globe bulbs, Haveli arch
- **Asymmetric masonry layout**: 3-column grid with 2 wide (span-2) hero cards
- **Category filter system** with animated GSAP transitions (collapse/expand)
- **Full-screen lightbox** with:
  - Back.out(1.2) easing for satisfying entry animation
  - Arrow key navigation (← →) and ESC to close
  - Touch swipe support for mobile
  - Click-outside-to-close behavior
  - Prev/Next slide transitions with directional awareness
- **Character-by-character heading animation** (SplitText-style manual implementation)
- **Staggered card scroll reveal** on viewport entry

### Footer Section Details
- **4-column rich footer grid**:
  - Brand column: Logo, description, Hindi tagline, social media icons (WhatsApp, Instagram, Facebook, YouTube)
  - Quick Links: About, Services, Gallery, Reviews, How We Work, Get a Quote
  - Services: Wedding Planning, Venue Decoration, Mehendi & Sangeet, Corporate Events, Birthday Parties, Rooftop Events
  - Contact & Hours: Full address, phone, email, business hours (24hr availability, consultation times, site visit appointments)
- Responsive: 4 cols → 2 cols (tablet) → 1 col (mobile)

### Navigation
- Fixed top navbar with transparent → solid transition on scroll
- **Logo integration**: Circular brand logo image (`images/logo.png`) with gold glow border + "Roshan Events" text + "रोशन इवेंट्स" Hindi tagline
- Logo scales down on scroll, gold glow intensifies on hover
- Desktop: smooth-scrolling links (About, Services, **Gallery**, Reviews, Contact) + Call Now CTA
- Mobile: hamburger menu with full-screen overlay and 6 staggered animation links

### Animations (13 total)
1. ✅ Canvas particle system (200-300 gold particles floating upward)
2. ✅ GSAP staggered hero text entrance
3. ✅ Count-up stat animations with eased interpolation
4. ✅ Scroll reveal on all section content (GSAP ScrollTrigger)
5. ✅ Service card hover effects (border glow, lift, icon scale)
6. ✅ SVG process line draw animation (scrub-based)
7. ✅ Testimonial auto-advance carousel with GSAP cross-fade
8. ✅ Parallax on hero glow element
9. ✅ WhatsApp FAB pulse animation (infinite CSS keyframes)
10. ✅ Nav background transition on scroll
11. ✅ Safety fallback: auto-reveal hidden content after 4 seconds
12. ✅ **Gallery heading character-by-character reveal**
12. ✅ **Gallery card hover effects (image zoom, overlay slide, category pill, expand icon)**
13. ✅ **Gallery filter GSAP collapse/expand with scale physics**

### Technical
- ✅ SEO meta tags (title, description, keywords, OG tags)
- ✅ LocalBusiness JSON-LD Schema markup
- ✅ `prefers-reduced-motion` respected — all animations disabled for accessibility
- ✅ Zero external images — all visuals via CSS gradients, SVG, and Canvas
- ✅ Responsive: 320px mobile → 768px tablet → 1200px+ desktop
- ✅ WhatsApp deep links with pre-filled Hindi message
- ✅ Touch swipe support on testimonial carousel and lightbox
- ✅ Keyboard accessibility for lightbox (ESC, arrows)
- ✅ Semantic HTML with ARIA labels

## 📁 File Structure
```
index.html                        — Main website (HTML + CSS + JS)
README.md                         — This documentation file
images/
  ├── logo.png                    — Brand logo (circular, blue/dark, 38 KB)
  ├── modern-elegance.jpg         — Wedding stage photo (75 KB)
  ├── grand-ballroom.jpg          — Reception hall photo (129 KB)
  ├── garden-night.jpg            — Outdoor event photo (81 KB)
  ├── starlight-wedding.jpg       — Grand outdoor photo (192 KB)
  ├── royal-jaipur.jpg            — Traditional setup photo (61 KB)
  ├── purple-dream.jpg            — Reception entry photo (135 KB)
  └── garden-mandap.jpg           — Wedding ceremony photo (107 KB)
```

## 🔗 Entry URI
- `/index.html` — Main (and only) page
- Anchor sections: `#about`, `#services`, `#gallery`, `#reviews`, `#process`, `#contact`

## 🖼️ Gallery Images

All 7 real event photographs are loaded from the `images/` directory:

| # | File | Card Type | Category |
|---|------|-----------|----------|
| 1 | `modern-elegance.jpg` | Standard | Wedding Stage |
| 2 | `grand-ballroom.jpg` | **Wide (span 2)** | Reception |
| 3 | `garden-night.jpg` | **Wide (span 2)** | Outdoor Event |
| 4 | `starlight-wedding.jpg` | Standard | Grand Outdoor |
| 5 | `royal-jaipur.jpg` | Standard | Traditional |
| 6 | `purple-dream.jpg` | Standard | Reception Entry |
| 7 | `garden-mandap.jpg` | Standard | Wedding Ceremony |

To replace any image, swap the file in the `images/` folder keeping the same filename.

## 🎨 Design System
| Token | Value | Usage |
|-------|-------|-------|
| Primary BG | `#0a0d1a` | Midnight navy — Rajasthan night sky |
| Surface | `#0f1428` | Cards, elevated surfaces |
| Footer BG | `#070a14` | Darker footer section |
| Gold | `#c9a84c` | Primary accent — aged jewelry gold |
| Champagne | `#f5e6c8` | Body text, secondary elements |
| Rose | `#8b2252` | Sparse accent — Rajasthani lehenga |
| Warm White | `#fdf6ec` | Headings, emphasis text |

### Typography
- **Headings**: Cormorant Garamond (serif) — palace invitation elegance
- **Body**: DM Sans (sans-serif) — clean, modern readability
- **Hindi**: Noto Serif Devanagari — for Hindi phrases

## 📦 External Dependencies (CDN only)
- **GSAP 3.12.5** + ScrollTrigger — `cdnjs.cloudflare.com`
- **Google Fonts** — Cormorant Garamond, DM Sans, Noto Serif Devanagari

## 🚀 Performance
- Gallery images total ~780 KB (7 optimized JPEGs)
- Canvas particle system capped at 60fps
- All CSS animations use GPU-composited properties
- Reduced motion media query bypasses all animations
- Gallery uses real photographs loaded from local `images/` directory

### Spacing & Layout Fixes (Latest)
- Reduced section padding from 120px to 80px for tighter, more professional feel
- Fixed GSAP `.reveal` animation using `fromTo()` instead of `from()` for reliable visibility
- Added `.revealed` CSS class as animation completion marker
- 4-second safety timeout auto-reveals any hidden content
- About section: changed mandala from 4:5 to 1:1 aspect ratio, reduced max-width
- Reviews section: added subtitle text
- Contact section: expanded from simple card layout to full 4-column rich footer

## 📋 Not Yet Implemented
- Blog / tips section
- Multi-language toggle (Hindi/English)
- Contact form with backend
- Analytics integration (Google Analytics, Facebook Pixel)

## 🔜 Recommended Next Steps
1. Update dummy footer data (email, Facebook, YouTube URLs) with real info
2. Add more event photographs to expand the gallery
3. Connect Google Analytics for traffic tracking
4. Add Facebook Pixel for ad retargeting
5. Set up Google My Business link for direct reviews
6. Add WhatsApp Business API for automated responses
7. Consider adding a pricing inquiry form

## Credits
- **Website by**: Ali
- **Client**: Roshan Events, Jaipur
- **Year**: 2025
