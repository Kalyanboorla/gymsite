# Triplomax Fitness High-Conversion Landing Page

This plan outlines the architecture and design strategy for creating a premium, high-conversion landing page for Triplomax Fitness. The focus will be on a human-crafted aesthetic that emphasizes trust, transformation, and fitness outcomes, leveraging vanilla HTML, CSS, and JS for maximum performance and design control.

## Proposed Changes

We will build an independent website structure within the current directory. 

### Core Site Files
#### [NEW] [index.html](file:///c:/Users/kalya/OneDrive/Desktop/websites/GYM%20sites/Triplomax%20Fitness/index.html)
The main structure with semantic HTML5 tags corresponding to:
- **Navigation/Header:** Logo + Sticky transparent/opaque transition navigation.
- **Hero Section:** High-energy animated section with the primary "Start Your Transformation" CTA. Includes background image/video treatment using `gym1.jpg` or visual cues.
- **Trust & Proof (Social Proof):** 4.8★ rating metric, 160+ members counter, transformation highlights, and review snippets.
- **Services Carousel/Grid:** Organized grouped services focusing on HIIT Training, Strength & Gym Training, Personal Training, and Transformation Programs.
- **Experience/About Section:** Using remaining gym asset imagery to convey standard and environment.
- **Instagram Integration:** A tailored masonry or grid preview mimicking an Instagram feed pointing to `@_triplomax_fitness_`.
- **Footer:** Essential links, location near SP College, WhatsApp direct chat link.

#### [NEW] [style.css](file:///c:/Users/kalya/OneDrive/Desktop/websites/GYM%20sites/Triplomax%20Fitness/style.css)
A highly customized vanilla CSS system utilizing:
- **CSS Variables:** Strictly mapped generic colors replaced with rich brand values (Red: `#D10000`, White, Deep Black `#0B0B0B`).
- **Typography Integration:** `Inter` or `Outfit` fonts linked from Google Fonts for sharp UI looks.
- **Animations:** Subtle reveal animations, CTA glowing pulses, floating effects on scroll.
- **Layouts:** Use of Flexbox and CSS Grid. Strong responsiveness focused heavily on a "mobile-first" experience.

#### [NEW] [script.js](file:///c:/Users/kalya/OneDrive/Desktop/websites/GYM%20sites/Triplomax%20Fitness/script.js)
Vanilla JavaScript to manage:
- Smooth scrolling and nav-bar background transition.
- Intersection Observers for subtle scroll-based element reveals (fade-ins, slide-ups).
- WhatsApp click tracking/handlers to format pre-filled queries (e.g., `https://wa.me/<number>?text=Hi,%20I%20want%20to%20join%20Triplomax%20Fitness`).
- Any dynamic metric counting animations (e.g. 0 to 160+ members).

#### [NEW] [package.json](file:///c:/Users/kalya/OneDrive/Desktop/websites/GYM%20sites/Triplomax%20Fitness/package.json)
Simple Vite dev server setup via standard NPM initialized script to provide hot-reloading for local review.

## User Review Required

> [!IMPORTANT]
> To link the pre-filled WhatsApp action buttons properly, please provide the actual phone number meant for Triplomax Fitness. If a number isn't provided right now, I will add a placeholder (e.g., `1234567890`) that you can easily edit later.
> 
> By approving this plan, I'll proceed strictly using modern vanilla Web technologies resulting in a premium custom aesthetic.

## Verification Plan

### Manual Verification
1. I will start the Vite dev server (`npm run dev`) and expose it to a browser session natively to ensure visual design and scrolling behaviours are as described.
2. I will ensure mobile layout works well.
3. Verify WhatsApp redirects correctly construct the pre-filled intent string.
