# NJ residential plumber (name unknown): handoff at ~60%

**Live:** https://10elizabethbell.github.io/njResidentialPlumbing/ · **Repo:** https://github.com/10elizabethbell/njResidentialPlumbing · **Built:** 2026-10-18 from Muse brief of 2026-10-18 (Facebook group sweep, ad posted by Nicole Andrews)

## What's built
- One page, `index.html` (about 41 KB, no images to load). Phone-first; desktop adds two-column services, a horizontal steps pipe and a side-by-side form.
- **World:** still water, copper pipe, porcelain-white sections. Navy ground (not black), copper is the only warm color (buttons, pipe, step markers), aqua is the form hover/focus color.
- **Hero:** "More than a quick fix." (from their own flyer line "Your home deserves more than just a quick fix"), their tagline, two buttons: **Get a free estimate** (to the form) and **Text us a photo** (outlined, `sms:`). Phone number top-right only.
- **Signature element:** a copper line with a ball valve crosses in from the right and drips into water at the bottom of the first screen. Drag a finger or mouse through the water to make waves (works up, down and sideways; pull-to-refresh is off), bubbles rise and dodge the pointer, drips splash. **Tap the red valve to stop the leak**; tap again to reopen. Animated water lines divide every section on one shared loop. Reduced motion gets a still frame.
- **Sections:** What we fix (7 short rows, each pre-picks that service in the form) → How it works (call or text, free estimate, fixed properly; numbered sweat couplings on a copper pipe) → Free estimate form → closing line in their words ("quality shouldn't be a luxury…") with the big tap-to-call number → footer (name, area, 24/7).
- **Contact:** all `tel:+18624000703`. The form needs service, how soon, name and town, then opens a text with the answers filled in; it also shows the message with a Copy button and a "call us" link in case texting doesn't work (desktop, or the number doesn't take texts). Picking "Right now" reveals "Water coming in right now? Calling is fastest: Call us".
- **Phone once per screen:** header top-right, then the closing section. The footer has no number because it sits on the same screen as the closing one (Ellie's rule against two controls doing the same thing in view). The valve gives a small wiggle every 7 seconds until someone taps it (`CFG.VALVE_HINT`).
- Favicon and home-screen icon: a copper drop on navy (there is no logo). `og.png` is the hero at 1200x630 for the Facebook preview.

## Assumptions I made
- **Name:** the header and footer say "Residential Plumbing" as a descriptor, not a business name. The brief says not to invent one or use the folder name. Swap in the real name in: `<title>`, the `.brand` header block, the footer `<b>`, og tags.
- **Voice:** "we". The flyer lists seven services and says "Professional Plumbing", which reads like a company, not a one-person shop. Switch to "I" if it's one plumber.
- **Texting:** the brief says texts are unknown (the ad only says call). I kept "Text us a photo" and the text-message form because they're the after-hours intake the brief says they lack, and paired both with calling. If the number can't take texts, change the hero's second button and make the form hand off by call.
- **Colors:** no brand on record. Navy, water blue and copper were chosen from the trade.
- **Audience:** not flagged 40+ in the brief, so the moving hero stays. If Ellie or the owner says their customers skew older, freeze it (`older-audience.md`).
- **Copy I wrote** (check with the owner): "Any hour, any day. Tell us what's leaking, clogged or not working." / "You know the price before we start. Fair, transparent, no surprises." (from "FREE ESTIMATES" + "FAIR & TRANSPARENT PRICING") / "Repaired the right way, not patched, so it stays fixed."
- Services were shortened from the flyer's wording (e.g. "Toilet Repairs & Installations" → "Toilets").

## Placeholders and gaps
- **Business name: unknown. Must be confirmed before handing over.**
- No logo, no work photos, no before/afters, no reviews, so there is no proof section. The flyer image needs a Facebook login to download.
- **No Facebook link on the page.** There's no business page, and the ad came from a personal profile whose link to the business isn't confirmed. Add it under a proof section and in the footer once they have a page (or confirm the profile is OK to use).
- No email, so none in the footer.
- No license or insurance claim (unverified). No years in business, no prices.

## Questions for the owner
1. What's the business name, exactly as you write it? Do you have a logo?
2. Does (862) 400-0703 take texts (and photos)?
3. Is it you on your own, or a crew? (I / we)
4. Licensed and insured in NJ? License number to show?
5. Any photos of jobs, before/afters, or reviews we can use?
6. Do you really cover all of New Jersey, or mainly the north (862 area)? Any towns you want named?
7. A business email and Facebook page for the footer?

## Ideas not built (yours to pick)
- **Runner-up world:** the copper line running down the whole page, with water flowing through it as you scroll and each section a fixture tapped off it. (The Impeccable roll assigned an isometric plumbing riser-diagram world; I used it only for the steps pipe because a drawing can't carry a touchable, fluid element as well as real water.)
- A short "Emergency right now?" line that switches to "Call" after 9pm local time.
- When photos arrive: a proof section with the photos sitting just under the water line, plus "Click to see more of my work." to Facebook.
- Before/after sliders (plain copper divider) once pairs exist.
- A clog you can clear: drag to unblock a drain and watch the water level drop.
- Name swap as one constant once known.

## Impeccable
- Ran: finish reviewer (disposition: fix, all 8 items applied or handled here) and a sweep of audit, critique, polish, harden, adapt, optimize, clarify, typeset, layout, colorize, animate, delight, distill, bolder, quieter, overdrive and extract. Skipped live (needs you) and onboard (no first-run flow). DESIGN.md written by the documenter.
- Not applied on purpose: a generic hero line ("We treat your home like it's our own"); I kept their own tagline. Sticky header and bottom bar, a Call button in the hero, and lighter or sentence-case headings were also skipped because they break your rules.
- Detector (not degraded): the closing quote's uppercase and tight line height are ignored for `index.html` in `.impeccable/config.json` (house style). `cramped-padding` is ignored too: a false positive, because the static parser can't read `max(var(--pad), env(safe-area-inset-*))`, and the screenshots show 20px gutters. Left standing: `flat-type-hierarchy` (body sizes 15/16/17/20/24). It's yours to tune.

## Not verified
- Real-device touch (iPhone/Android, Facebook in-app browser): the drag in the water, the valve tap, and that a drag starting in the water doesn't scroll (intended).
- Real SMS handoff on iOS and Android, including the `?&body=` format.
- Frame rate on older phones.
