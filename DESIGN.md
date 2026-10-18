---
name: Residential Plumbing, New Jersey
description: A plumber's promise told in its own material, still water, copper pipe and a drip you can stop.
colors:
  navy: "#0e2a3b"
  navy-2: "#123447"
  deep: "#0b4a63"
  porcelain: "#eef3f4"
  porcelain-2: "#dfe8ea"
  line: "#7d939d"
  ink: "#10232e"
  ink-soft: "#3c5664"
  mist: "#c9dbe2"
  white: "#ffffff"
  copper: "#d68b55"
  copper-hi: "#efb183"
  copper-lo: "#9a5329"
  aqua: "#1f8fb0"
  aqua-hi: "#6fd0e6"
  error: "#a3321f"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(46px, 13.6vw, 104px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(36px, 10vw, 64px)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  quote:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(30px, 8.4vw, 60px)"
    fontWeight: 900
    lineHeight: 1.06
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 900
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  list-item:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.55
    letterSpacing: "-0.01em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.55
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"SF Pro Display\", \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  pill: "999px"
  field: "12px"
  panel: "14px"
  circle: "50%"
spacing:
  pad-phone: "20px"
  pad-wide: "40px"
  section-phone: "56px 0 64px"
  section-wide: "88px 0 96px"
  container: "1180px"
components:
  button-primary:
    backgroundColor: "{colors.copper}"
    textColor: "{colors.navy}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.copper-hi}"
    textColor: "{colors.navy}"
  button-outline-dark:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "56px"
  button-outline-light:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "48px"
  chip:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
  input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "14px 16px"
    height: "54px"
  service-row:
    textColor: "{colors.ink}"
    typography: "{typography.list-item}"
    padding: "10px 2px"
    height: "64px"
  service-row-arrow:
    backgroundColor: "{colors.porcelain-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  service-row-arrow-hover:
    backgroundColor: "{colors.copper}"
    textColor: "{colors.navy}"
  panel:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "18px"
---

# Design System: Residential Plumbing, New Jersey

## Overview

**Creative North Star: "Still Water and Sweat-Soldered Copper"**

The system is built from the trade's own materials. Dark sections are water at depth: a navy ground that deepens toward teal at the bottom of the hero, where a live canvas surface swells, bubbles, and takes a drip from a copper line. Light sections are porcelain fixtures: cool, clean, slightly blue whites with ink text. Copper is the one warm material in the whole world, and it marks everything a homeowner should act on, plus the pipe and the couplings that join the three steps.

Type is loud and plain. The owner chose the system font stack with heavy (900) uppercase display headings; it reads like a truck door or a trade flyer, which is the point. Everything else is calm: generous phone-first spacing, flat surfaces, no cards stacked on cards, no ornament that is not water or pipe. Sections are joined by animated water seams, not rules or hard edges.

The page is phone first and single column until 760px. The phone number sits top-right on the first screen and again, huge, at the close; there is no sticky header and no sticky bottom bar.

**Key Characteristics:**
- Navy-to-deep-water dark grounds alternating with porcelain light sections, joined by animated three-line water seams.
- Copper is the only warm color in the interface; aqua is the interaction color for form controls and focus.
- System font stack, weight 900, uppercase, tight tracking (-0.02em) and sub-1 line height for every heading.
- Pill buttons and chips, softly rounded fields, circles for arrows; no sharp-cornered controls.
- Flat surfaces. Depth comes from gradients of water and the metallic shading of copper, never from drop shadows.

## Colors

A cool, wet palette (navy, deep teal, porcelain, mist) with copper as the single warm accent and aqua as the single interaction accent.

### Primary
- **Sweat-Soldered Copper** (copper): every primary action fill (Get a free estimate, Text my free estimate request), phone icons, the service-row arrow on hover, the brand drop. Navy text sits on it.
- **Polished Copper** (copper-hi): hover state for copper fills and for the phone links on navy.
- **Oxidized Copper** (copper-lo): the text caret in fields; the dark end of the copper metal gradients.

### Secondary
- **Pool Aqua** (aqua): form control hover and focus edges, focus outlines on light sections, the text selection highlight.
- **Surface Light Aqua** (aqua-hi): focus outline on dark sections.

### Neutral
- **Night Water Navy** (navy): page ground, hero top, footer, the selected chip, text on copper.
- **Pipe-Run Navy** (navy-2): the How it works ground, one step lighter than the page.
- **Deep Water** (deep): bottom of the hero gradient and top of the closing gradient.
- **Porcelain** (porcelain): light section ground (services, estimate).
- **Porcelain Shadow** (porcelain-2): row dividers, idle arrow discs, the sent-message panel edge.
- **Fixture Grey-Blue** (line): idle 2px edges on chips and fields.
- **Ink** (ink): text on porcelain and white.
- **Soft Ink** (ink-soft): secondary text on porcelain (ledes, notes, "optional").
- **Mist** (mist): secondary text on navy (taglines, step copy, footer).
- **White** (white): text on navy; field and chip fills.
- **Error Brick** (error): error message text in the form. It is a state color, not decoration.

### Named Rules
**The One Warm Metal Rule.** Copper is the only warm color in the interface. It marks actions and pipe; nothing else in the UI is orange, red, yellow or brown, except the error-brick state color on invalid form fields. Illustrated fixtures in the hero canvas (the brass valve body and its red lever) are depictions of real hardware and are exempt; they never become UI colors.

**The Aqua Means Touch Rule.** Aqua appears only where the user is interacting: hover and focus on form controls, focus outlines, selection. It is never a fill for content or decoration.

## Typography

**Display Font:** System stack (-apple-system, SF Pro Display, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** Same system stack

**Character:** One family, two voices. Headings shout in weight 900 uppercase with tight tracking, like trade lettering; body copy is plain 17px at a relaxed 1.55 line height. This is the owner's stated taste, not a default to be "upgraded."

### Hierarchy
- **Display** (900, clamp(46px, 13.6vw, 104px), 0.98, uppercase): the hero line only, held to about 9ch.
- **Headline** (900, clamp(36px, 10vw, 64px), 0.98, uppercase): section titles.
- **Quote** (900, clamp(30px, 8.4vw, 60px), 1.06, uppercase): the closing customer-quality line, about 18ch.
- **Title** (900, 24px, 1.05, uppercase): step titles.
- **List item** (800, 20px, -0.01em): service rows; sentence case.
- **Body** (400, 17px, 1.55): all paragraphs, 34 to 44ch measures.
- **Label** (800, 16px): form legends and labels; "optional" drops to 500 in soft ink.
- **Button** (800, 17px, 1): button text, sentence case.
- **Small** (15px): notes, error text (700), footer.

The closing phone number is display-scale (900, clamp(30px, 9vw, 52px)) with tabular figures; all phone numbers use tabular-nums.

### Named Rules
**The Heavy Caps Rule.** Every h1, h2, h3 and the closing quote is weight 900, uppercase, -0.02em tracking, line height under 1.1, with balanced wrapping. Buttons, labels, service rows and body stay in sentence case.

## Layout

Phone first, single column, with a 1180px max container and side padding of 20px (40px from 760px), respecting safe-area insets. Sections pad 56px top / 64px bottom on phones and 88px / 96px from 760px. Inner rhythm uses 10 to 28px gaps: 12px between stacked buttons, 22px between form groups, 28px before lists and forms.

- **Under 760px:** hero actions stack full width up to 420px; services are one list; steps run vertically along a copper pipe.
- **760px and up:** hero actions sit side by side; services split into two columns of four (filling column-first); steps become three columns along a horizontal pipe; seams grow from 46px to 70px.
- **1024px and up:** the estimate section becomes a 5fr/7fr split with the heading sticky beside the form; the closing quote and phone number sit side by side, bottom-aligned.

The hero fills the first screen (up to 980px tall): header bar, copy, then the water pool taking the remaining height (at least 190px).

### Named Rules
**The Number Top-Right Rule.** On the first screen the phone number appears only in the header's top-right corner. The hero carries Get a free estimate and Text us a photo, never a third call button.

**The Nothing Sticks Rule.** No sticky header and no sticky bottom bar. The only sticky element is the estimate heading column on wide screens.

## Elevation & Depth

The system is flat. No drop shadows on any surface or control. Depth comes from the materials: vertical gradients on dark sections (navy to deep water in the hero, deep water back to navy at the close), the layered canvas water, and the metallic banded gradients of copper pipe and couplings. The only box-shadow is a 3px aqua halo (rgba(31,143,176,.25)) on focused text fields.

### Named Rules
**The Water Not Shadow Rule.** Separate planes with ground color and the animated water seams, never with shadows or cards floating on cards.

## Shapes

Controls are soft. Buttons and chips are full pills (999px); fields are gently rounded (12px); the one panel (the sent-message box) is 14px; arrows are circles. Edges are 2px solid on interactive controls and 1px hairlines for list dividers. The step markers are small copper couplings (5px corners with ring bands) on a 12px-thick rounded copper pipe that runs vertically on phones and horizontally from 760px. Section boundaries are always water seams: a filled wave plus three thin animated lines in aqua tones.

## Components

### Buttons
Big, round, and obvious.
- **Shape:** full pill (999px), 56px tall, 24px side padding, 2px border, icon gap 10px with 20px SVG icons.
- **Primary:** copper fill and border, navy text. Hover goes to polished copper. Press scales to 0.98.
- **Outline on dark:** transparent with a 75% white border and white text; hover brings the border to full white and adds an 8% white wash.
- **Outline on light:** transparent with ink border and text, 48px tall (copy message).
- **Inside the form:** the submit and copy buttons also take a 3px aqua outline (3px offset) on hover and focus, matching the other form controls.

### Chips
- **Style:** 46px pill, white fill, 2px fixture grey-blue edge, 700 16px text, wrapping with 10px gaps. Real radio inputs underneath.
- **State:** hover turns the edge aqua; keyboard focus adds a 3px aqua outline. Selected turns navy fill with white text; a selected chip on hover gets an aqua edge plus a 2px aqua outline.

### Inputs / Fields
- **Style:** white fill, 2px fixture grey-blue edge, 12px radius, 14px 16px padding, 54px min height (textarea 110px), 500 17px ink text, copper-lo caret, placeholder #5f7784.
- **Hover:** edge turns aqua.
- **Focus:** edge aqua plus the 3px translucent aqua halo; no browser outline.
- **Error:** the group shows a 700 15px error-brick message and the control edge turns red.

### Navigation
A single header bar inside the hero: brand mark (copper drop, 30px) with "Residential Plumbing" in 900 uppercase 15px and "New Jersey · 24/7" in 13px mist, and the phone number at the right in 800 16 to 17px with a copper phone icon. The phone link warms to polished copper on hover. Not sticky.

### Service Rows (signature)
Full-width 64px rows with 1px porcelain-shadow dividers, 800 20px label on the left, a 44px circular arrow disc on the right. On hover the row itself does nothing; only the arrow disc turns copper with navy arrow. Keyboard focus puts the copper on the arrow and a 3px aqua outline around it. Tapping a row pre-selects that service in the estimate form.

### Copper Pipe Steps (signature)
Three numbered steps strung on a copper pipe; each number sits in a copper coupling (34 by 46px on phones, 46 by 34px wide) with darker ring bands at both ends. Numbers are 900 20px navy. Copy is mist on the pipe-run navy ground.

### Water Seams (signature)
Every boundary between sections is an animated SVG wave: the lower section's color as a filled wave over the upper section's color, plus three non-scaling lines (rgba(111,208,230,.55) at 2px, #2c93ae at 3.2px, rgba(191,230,238,.7) at 1.6px). All seams and the hero water share one animation loop, pause off screen, and hold still under reduced motion.

### Hero Water (signature)
A canvas pool along the bottom of the hero: spring-column surface with layered swell, rising bubbles, a copper line entering from the right with a ball valve and an open end that drips. Pointer and finger stir the water; tapping the valve stops the drip. It is decoration only (aria-hidden) and never carries information.

## Do's and Don'ts

### Do:
- **Do** use copper (#d68b55) for primary action fills with navy text, and polished copper (#efb183) for their hover.
- **Do** set every heading in the system stack at weight 900, uppercase, -0.02em, line height under 1.1.
- **Do** give text fields, chips and buttons inside the form an aqua (#1f8fb0) edge or outline on hover and focus.
- **Do** keep service rows still on hover and move only the arrow disc to copper.
- **Do** join sections with the animated water seam, coloured from the upper section to the lower.
- **Do** keep tap targets at least 44px, and 56px for primary buttons.
- **Do** pair every text path with a way to call.

### Don't:
- **Don't** introduce any other warm color into the interface; copper is the only one. The error state and illustrated hardware in the hero canvas are the only exceptions.
- **Don't** add a sticky header or a sticky bottom call bar.
- **Don't** put the phone number anywhere on the first screen except the header's top-right.
- **Don't** swap the system stack for a webfont or lighten or sentence-case the headings; this is the owner's choice.
- **Don't** use drop shadows or floating cards to separate content.
- **Don't** use aqua as a decorative or content color.
- **Don't** add a background, shadow or outline to a whole service row on hover.
