---
name: SerTec Refrigeração
description: Local refrigeration and air-conditioning specialists in Sapucaia do Sul, RS — fast service, real reviews, direct contact.
colors:
  midnight-navy: "#0F172A"
  navy-surface: "#1E293B"
  workshop-blue: "#0369A1"
  sky-active: "#0EA5E9"
  deep-blue: "#075985"
  off-white: "#F8FAFC"
  pure-white: "#FFFFFF"
  cloud-gray: "#F1F5F9"
  border-gray: "#E2E8F0"
  placeholder-gray: "#CBD5E1"
  steel-gray: "#64748B"
  charcoal: "#334155"
  ink: "#020617"
  sky-highlight: "#7DD3FC"
  ice-blue-tint: "#DBEAFE"
  whatsapp-green: "#25D366"
  whatsapp-deep: "#128C7E"
  amber-star: "#F59E0B"
  error-red: "#EF4444"
typography:
  display:
    fontFamily: "Poppins, sans-serif"
    fontSize: "clamp(32px, 5vw, 56px)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "normal"
  headline:
    fontFamily: "Poppins, sans-serif"
    fontSize: "clamp(26px, 3.5vw, 40px)"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "normal"
  title:
    fontFamily: "Poppins, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: "normal"
  body:
    fontFamily: "Poppins, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: "normal"
  label:
    fontFamily: "Poppins, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.05em"
rounded:
  sm: "8px"
  md: "12px"
  lg: "20px"
  pill: "100px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "48px"
  xl: "80px"
components:
  button-primary:
    backgroundColor: "{colors.workshop-blue}"
    textColor: "{colors.pure-white}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
  button-primary-hover:
    backgroundColor: "{colors.deep-blue}"
    textColor: "{colors.pure-white}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.pure-white}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
  button-whatsapp:
    backgroundColor: "{colors.whatsapp-green}"
    textColor: "{colors.pure-white}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
  button-whatsapp-hover:
    backgroundColor: "{colors.whatsapp-deep}"
    textColor: "{colors.pure-white}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
  section-tag:
    backgroundColor: "{colors.ice-blue-tint}"
    textColor: "{colors.workshop-blue}"
    rounded: "{rounded.pill}"
    padding: "4px 12px"
  service-card:
    backgroundColor: "{colors.off-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "32px"
  form-input:
    backgroundColor: "{colors.pure-white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: "12px 16px"
---

# Design System: SerTec Refrigeração

## 1. Overview

**Creative North Star: "The Workshop Specialist"**

SerTec looks like a business that has done ten thousand service calls. Not a startup, not a franchise — a local specialist with calluses. The design carries that credibility through directness: a dark navy hero that commands authority without apology, content sections that stay clean and scannable on a budget Android screen, and every scroll stop ending with a clear next action. Nothing exists for decoration; everything earns its place by moving the user toward a WhatsApp message.

The palette splits the site cleanly into two environments: the deep midnight navy of the hero and footer, where trust is established, and the white-to-off-white content body, where specifics are delivered. The accent blue is never ambient — it fires only on interactive elements (CTAs, links, icons in context wells) so the eye always knows where to go next.

This system explicitly rejects generic HVAC SaaS templates with dark blue grids and abstract "AI-powered" icons. It rejects overdone glassmorphism, animated hero videos, and the cold anonymity of national chains. The site should feel like the owner could walk in the door.

**Key Characteristics:**
- Light-mode content sections (white/off-white), dark hero and footer for authority framing
- Accent blue reserved for action — never used as a decorative background
- Poppins at high weight contrast (400 body, 700–800 display) for clear hierarchy on small screens
- Flat surfaces at rest; elevation appears only on hover as a reward for engagement
- WhatsApp green is a peer to the primary blue — a second CTA color with equal weight
- Touch targets never smaller than 44px; copy direct and never padded

## 2. Colors: The Workshop Palette

A two-environment palette: the deep navy frames trust, the near-white body delivers information, and the workshop blue converts.

### Primary
- **Midnight Navy** (`#0F172A`): The dominant structural color. Hero section, footer, logo mark, all primary headings. This is the color of authority — not chosen for trend, chosen because it reads as serious and local.
- **Navy Surface** (`#1E293B`): A single step lighter than Midnight Navy. Used sparingly for layered surfaces within dark contexts.

### Secondary
- **Workshop Blue** (`#0369A1`): The primary action color. Every CTA button, every anchor link, every icon container tint references this hue. Used for interactive affordances only — never as a section background or decorative block.
- **Sky Active** (`#0EA5E9`): The lighter variant used for focus rings (`outline: 3px solid`) and footer contact icon accents. Never a fill color on interactive elements — that's Workshop Blue's job.
- **Deep Blue** (`#075985`): The hover state for Workshop Blue. Slightly darker, signals state change without a dramatic shift.

### Tertiary
- **WhatsApp Green** (`#25D366`): Treated as a second primary action color alongside Workshop Blue. The floating contact button and the in-hero CTA use this. Its hover state is Whatsapp Deep (`#128C7E`).
- **Amber Star** (`#F59E0B`): Restricted to the star rating system and the Google review banner. Never decorative.

### Neutral
- **Off-White** (`#F8FAFC`): The default page background. Alternating sections use Pure White and Off-White to create rhythm without borders.
- **Pure White** (`#FFFFFF`): Form inputs, header background, explicit white surfaces.
- **Cloud Gray** (`#F1F5F9`): Alternate section background (the "Sobre" section).
- **Border Gray** (`#E2E8F0`): All borders — card outlines, form inputs at rest, dividers.
- **Steel Gray** (`#64748B`): Muted body text, form labels, secondary information. All muted text resolves to this.
- **Charcoal** (`#334155`): Review quote text — slightly darker than Steel Gray for longer italic passages.
- **Ink** (`#020617`): Primary body text. Near-black, tinted blue, never flat black.
- **Sky Highlight** (`#7DD3FC`): The single decorative tint — used only for the accented word in the hero title.
- **Ice Blue Tint** (`#DBEAFE`): Icon container backgrounds, section tag fills. Never a card or section background.

### Named Rules
**The Workshop Blue Rule.** Workshop Blue (`#0369A1`) appears only on interactive elements and their direct containers. It is never used as a section background, decorative stripe, or ambient fill. Rarity is what makes it scannable.

**The Dark-Light Split Rule.** Hero and footer are always Midnight Navy. Content sections are always white or off-white. Never mix: no dark content cards inside light sections, no white-background islands inside the dark hero.

## 3. Typography

**Body Font:** Poppins (weights 300–800), sans-serif, loaded from Google Fonts.

**Character:** Poppins is geometric but warm — wide apertures and friendly terminals that keep it readable at 13px on a low-res screen while still carrying authority at 56px display weight. The system spans from 300 (hero subtitle) through 800 (hero title) — this six-step weight range is the entire typographic palette. No secondary face.

### Hierarchy
- **Display** (800 weight, `clamp(32px, 5vw, 56px)`, line-height 1.15): Hero headline only. Bold enough to read on a phone at arm's length. Used once per page.
- **Headline** (700 weight, `clamp(26px, 3.5vw, 40px)`, line-height 1.25): Section titles (`section-title`). One per section.
- **Title** (700 weight, 20–22px, line-height 1.4): Card headings, contact info block headers, form card header.
- **Body** (400–500 weight, 15–17px, line-height 1.6–1.7): Section subtitles, card descriptions, form field text. Body line length is naturally capped by the section subtitle's `max-width: 560px`.
- **Label** (600 weight, 12–13px, letter-spacing 0.05em, uppercase): Section tags, form field labels, contact item labels. Always uppercase, always tracked out.

### Named Rules
**The Weight-Only Hierarchy Rule.** All type is Poppins. Hierarchy is established exclusively through weight and size — never through a secondary typeface. The difference between a card heading (600, 18px) and body text (400, 14px) must be immediately legible on a mid-range Android screen.

## 4. Elevation

The system is flat by default. Surfaces at rest carry no shadow — separation between sections is achieved by alternating background colors (white / off-white / midnight-navy), not by lifting cards off a base.

Shadows appear only in response to state. A hovered card earns depth; a resting card does not. This keeps the page feeling clean and fast to paint — no compound shadow calculations on initial load.

### Shadow Vocabulary
- **Ambient** (`0 1px 3px rgba(0,0,0,.08), 0 1px 2px rgba(0,0,0,.06)`): Header on scroll. Barely perceptible — signals the header has separated from the page.
- **Lifted** (`0 4px 16px rgba(0,0,0,.08)`): Hover state for buttons and review cards. Clear but soft — lifts without drama.
- **Featured** (`0 10px 40px rgba(0,0,0,.12)`): Hover state for service cards at peak engagement. The most dramatic shadow in the system, and still restrained.

### Named Rules
**The Flat-By-Default Rule.** A card with a shadow at rest is a card that has already spent its elevation budget. Reserve shadows for interaction — the hover lift should feel like a response, not a default.

## 5. Components

### Buttons

*Solid and direct. The button says what it does.*

- **Shape:** Gently curved (8px radius, `--radius-sm`).
- **Primary** (`.btn-primary`): Workshop Blue fill (`#0369A1`), Pure White text. Padding 14px / 28px. Font: Poppins 600, 15px.
- **Hover:** Deepens to `#075985`, translates -1px on Y-axis, acquires the Lifted shadow. Transition 200ms ease.
- **Focus visible:** 3px solid Sky Active (`#0EA5E9`) outline, 2px offset. Visible and distinct from hover.
- **Outline** (`.btn-outline`): Transparent fill, Pure White text, `rgba(255,255,255,.5)` border. For use on dark backgrounds only (hero). Hover: border goes fully white, fill picks up 10% white tint.
- **WhatsApp** (`.btn-whatsapp`): WhatsApp Green (`#25D366`) fill, Pure White text. Hover: deepens to `#128C7E`. Shares all other button specs.
- **Small variant** (`.btn-sm`): 10px / 20px padding, 14px font.

### Section Tags

*Pill-shaped category labels that orient the user before they read the heading.*

- **Style:** Ice Blue Tint background (`#DBEAFE`), Workshop Blue text. Fully rounded (100px). 4px / 12px padding. Poppins 600, 12px, uppercase, 0.5px letter-spacing.
- **Dark variant** (inside midnight-navy sections): `rgba(255,255,255,.15)` background, Pure White text.

### Cards / Containers

*Flat at rest. Hover earns depth.*

- **Service Card:** Off-White background, Border Gray (`#E2E8F0`) 1px border, 12px radius. Padding 32px. At rest: no shadow. Hover: border shifts to Sky Active, acquires Featured shadow, -4px Y translate.
- **Review Card:** Same structure as Service Card but padding 28px. Hover: acquires Lifted shadow only (no border-color change).
- **Differentials Card** (inside dark section): `rgba(255,255,255,.06)` fill, `rgba(255,255,255,.1)` border. Hover: fill to 10%, border to 20% white, -4px Y translate. No shadows — elevation is expressed through fill opacity, not shadows, on dark surfaces.
- **Contact Form Card:** Off-White background, Border Gray border, 12px radius. Padding 36px. No hover state — it's a static container.
- **About Metrics Block:** Semi-transparent white fill (`rgba(255,255,255,.12)`) on the dark gradient — the one purposeful use of a translucent surface. A contained 4px `backdrop-filter: blur` keeps it from reading as decorative glassmorphism.

### Inputs / Fields

*Stroked, white-fill, focus-glow. No fill-shift on focus — only the border color and a soft blue glow change.*

- **Style:** White background, Border Gray 1.5px border, 8px radius. Poppins 400, 15px.
- **Focus:** Border shifts to Workshop Blue (`#0369A1`); glow appears: `0 0 0 3px rgba(3,105,161,.12)`. No outline — the glow IS the focus ring for mouse users.
- **Error:** Border shifts to Error Red (`#EF4444`); glow: `0 0 0 3px rgba(239,68,68,.1)`.
- **Placeholder:** Placeholder Gray (`#CBD5E1`).
- **Select:** Same as input, with an inline SVG chevron at right 12px (Steel Gray stroke).
- **Textarea:** Vertically resizable only (`resize: vertical`), `min-height: 110px`.

### Navigation

*Clean and unobtrusive — the header should not compete with the hero.*

- **Default state:** Pure White background, Border Gray 1px bottom border. Poppins 500, 14px, Charcoal (`#334155`) text. 8px / 14px padding per link, 6px radius.
- **Hover:** Color shifts to Workshop Blue, background picks up Off-White tint. 200ms ease.
- **Active/current:** No distinct style in the current implementation — handled by scroll position.
- **Scrolled state:** Header acquires Lifted shadow (`0 4px 16px rgba(0,0,0,.08)`).
- **Mobile:** Nav links hidden; hamburger appears (24px wide, 2px Midnight Navy bars). Mobile nav drops below header with border-top, full-width links separated by Border Gray borders.

### Floating WhatsApp Button (Signature Component)

*The one permanently visible conversion trigger. It must always be unmistakable.*

- **Style:** WhatsApp Green fill, Pure White text, Poppins 600, 14px, pill shape (50px radius). Fixed bottom-right (28px from each edge). Shadow: `0 8px 32px rgba(37,211,102,.4)` — a colored shadow that matches the button's own hue.
- **Hover:** Darkens to `#128C7E`, shadow deepens to `0 12px 40px rgba(37,211,102,.45)`, -2px Y translate.
- **Notification dot:** 16px circle, Error Red (`#EF4444`), top-right corner, 2px Pure White border. Animated pulse ring: `scale(2.2)` over 2s, fading to opacity 0. Signals urgency without requiring interaction.
- **Mobile:** Label text hidden; button collapses to a 48px circle.

## 6. Do's and Don'ts

### Do:
- **Do** alternate section backgrounds (Pure White / Off-White / Midnight Navy) to create page rhythm. This is the only elevation mechanism at rest.
- **Do** use Workshop Blue exclusively for interactive elements. Its scarcity makes it scannable.
- **Do** lead every section with a pill-shaped section tag, followed immediately by the headline. This is the section header pattern — never skip the tag.
- **Do** include a WhatsApp or phone CTA within every major section. "Action at every scroll stop" is the conversion principle.
- **Do** keep body line length at or under `max-width: 560px` for section subtitles. Longer lines are never warranted on this site.
- **Do** respect `prefers-reduced-motion` — all transitions and animations are already gated on this media query. New animations must follow the same pattern.
- **Do** size all touch targets at 44px minimum. The audience is on mobile, often in a hurry.

### Don't:
- **Don't** use glassmorphism decoratively. The single use of `backdrop-filter: blur(4px)` on the About metrics block is purposeful and contained. Blurred, translucent cards as a general design pattern are explicitly prohibited.
- **Don't** use dark blue grids, abstract tech icons, or "AI-powered" marketing language. This is not a generic HVAC SaaS template.
- **Don't** make the site feel like a national chain — cold, anonymous, corporate. Real names, real ratings, real address are the trust signals. Never substitute them with abstract brand claims.
- **Don't** use `border-left` or `border-right` greater than 1px as a colored decorative stripe on any card or list item. Use background tints, leading icons, or full borders instead.
- **Don't** apply Workshop Blue to section backgrounds, decorative blocks, or ambient fills. Every appearance of that color must be actionable.
- **Don't** animate CSS layout properties (`width`, `height`, `padding`, `margin`). Transitions are limited to `transform`, `box-shadow`, `border-color`, `background-color`, and `color`.
- **Don't** add shadow to cards at rest. The Flat-By-Default Rule is a load performance choice as much as a design one.
- **Don't** use animated hero videos or parallax effects. Speed above decoration — the audience is on 4G.
