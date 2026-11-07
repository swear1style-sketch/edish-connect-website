---
version: alpha
name: "Fitness template by 8B"
description: "Framed white, navy and pale slides floating on a blue-grey mist for a gym, training club or coaching studio, with streaking type and orbiting rings. Free HTML template by 8B, MIT."
colors:
  primary: "#0b1019"
  secondary: "#536477"
  tertiary: "#2f54e0"
  neutral: "#dbe4ec"
  surface: "#ffffff"
  on-surface: "#0b1019"
  navy: "#1a2333"
  mist: "#9db1c4"
  panel: "#edf2f6"
typography:
  headline-display:
    fontFamily: Geist
    fontSize: 150px
    fontWeight: 500
    lineHeight: 0.86
    letterSpacing: -0.065em
  headline-lg:
    fontFamily: Geist
    fontSize: 96px
    fontWeight: 500
    lineHeight: 0.92
    letterSpacing: -0.055em
  headline-md:
    fontFamily: Geist
    fontSize: 50px
    fontWeight: 500
    lineHeight: 1.04
    letterSpacing: -0.045em
  title-md:
    fontFamily: Geist
    fontSize: 27px
    fontWeight: 500
    lineHeight: 1.08
    letterSpacing: -0.035em
  body-lg:
    fontFamily: Geist
    fontSize: 21px
    fontWeight: 400
    lineHeight: 1.38
    letterSpacing: -0.015em
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: -0.005em
  label-md:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: 0em
  button:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: -0.01em
  wordmark:
    fontFamily: Geist
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: -0.06em
rounded:
  none: 0px
  full: 999px
spacing:
  slide-padding: 44px
  page-gutter: 48px
  section-gap: 112px
  slide-max: 1180px
  tile-gap: 18px
  card-gap: 24px
  nav-height: 56px
  control-height: 48px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: "0 24px"
    height: "{spacing.control-height}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: "0 24px"
    height: "{spacing.control-height}"
  nav-bar:
    backgroundColor: "rgba(255, 255, 255, 0.72)"
    textColor: "{colors.primary}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: "0 8px 0 20px"
    height: "{spacing.nav-height}"
  slide-white:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.none}"
    padding: "{spacing.slide-padding}"
  slide-navy:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.surface}"
    rounded: "{rounded.none}"
    padding: "{spacing.slide-padding}"
  badge-tag:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.full}"
    padding: "6px 11px"
  input-field:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.primary}"
    typography: "{typography.body-md}"
    rounded: "{rounded.none}"
    padding: "12px 14px"
    height: "{spacing.control-height}"
  plan-featured:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.surface}"
    rounded: "{rounded.none}"
    padding: 24px
---

## Overview

Arcline is a one-page site for a gym, training club or coaching studio that sells measured, coached training: a test, a block of weeks, a retest. The one idea is a set of framed slides with small corner crosshairs, floating on a fixed blue-grey mist crossed by thin circles. White, navy and pale slides alternate and step left or right down the page. The feeling is calm and precise, closer to a sports lab than a gym floor; the energy comes from motion, not colour.

## Colors

The page is almost colourless on purpose: ink, navy, white and a family of blue-greys.

- **Primary (#0b1019):** near-black ink for text and for dark buttons, and the colour of the thin rule under the contact heading.
- **Secondary (#536477):** slate for secondary text, small labels, step numbers and field labels.
- **Tertiary (#2f54e0):** cobalt blue, the only saturated colour. It appears only as the keyboard focus ring (white on navy slides) and the border of a focused form field.
- **Neutral (#dbe4ec):** the misty page background behind everything.
- **Surface (#ffffff):** white slides, white pill buttons on dark slides and the nav bar tint.
- **On-surface (#0b1019):** text on white and pale slides.
- **Navy (#1a2333):** navy slides (the cover, the lab, the footer, the featured plan and the phone menu) and the tint of every shadow.
- **Mist (#9db1c4):** hairline rules, ring outlines, field borders and the fog in the page background.
- **Panel (#edf2f6):** pale panels, the rest-day card, form fields and the pale middle stop of the sphere gradient.

## Typography

One family, **Geist**, loaded as a variable font for weights 400 to 600. One face keeps the page quiet and lets size do the talking.

- **Display and headlines** are weight 500 with strong negative tracking (from -0.045em up to -0.065em) and line heights under 1. The cover headline is sized from its slide width, then set per line through a `--len` character count so each line fills its width. Section headings run from roughly 34px on phones to about 100px on a wide desktop; the cover headline and the footer wordmark are the largest type on the page.
- **Body** is Geist 400 at 16px with a line height of 1.55; intro paragraphs are 18px to 21px.
- **Labels and buttons** are weight 500 at 13px and 15px, never uppercase and never widely tracked.
- **Wordmark:** "arcline" in the nav is set in lower case at weight 600 with tight tracking (-0.06em), followed by a small superscript registered sign; the footer repeats it at display size in weight 500.

## Layout

Every section is a framed slide inside a page gutter of up to 48px, separated by up to 112px of mist. Slides have different maximum widths (1040px to 1180px) and sit left or right, so the column zigzags. Inside a slide the grids are loose: a 6-column collage of photo tiles, four portraits at staggered heights, a three-column plan row divided by hairlines, a day-card track that runs sideways.

At 900px and below the nav links collapse into a round menu button and a full-screen navy menu with links up to 64px. At 860px and below multi-column grids become one or two columns, the sports collage turns into two columns with rows of 118px, and the day cards become 78vw wide. At 767px and below the cover puts the photo on top and the headline over it.

## Elevation & Depth

Depth is layered, not heavy. Slides carry one wide, soft navy shadow (offset 40px, blur 90px, spread -50px). Spheres use a tighter one (offset 40px, blur 80px, spread -30px). The nav bar adds a 16px backdrop blur to its 72% white tint. Behind it all, a fixed background of two thin white circles and soft radial glows gives the mist some structure.

## Shapes

Slides, photos, tiles and form fields have square corners. Everything interactive and small is a pill: buttons, the nav bar, badges. Icon buttons, sphere ornaments, round photo chips and the lab lens are circles. Corner crosshairs (13px, 1px lines, 16px in from two opposite corners) mark every slide. Orbit rings are 1px SVG circles that draw on. Spheres are CSS radial gradients, not images. Photos are desaturated, and the coach portraits are fully grayscale.

## Components

- **button-primary:** ink pill, white 15px label, 48px high, 24px side padding. **button-secondary** is the white version for dark slides.
- **nav-bar:** a floating 56px pill with 72% white and blur, wordmark, a short line, section links and one dark Book a test button.
- **slide-white / slide-navy:** the two main containers, with the crosshair corners and the soft shadow. A third, pale slide uses a 140 degree gradient from white through panel to neutral, and carries the coaches, stories and FAQ.
- **badge-tag:** a small white pill laid over a photo tile.
- **input-field:** 48px, pale panel fill, mist border, square corners; the cobalt border shows on focus.
- **plan-featured:** the middle membership plan inverted to navy. The plan row is divided by hairlines, not by cards.
- **Text links:** 15px with a 1px underline that sweeps out and back on hover.

## Motion

The page loads no animation library. Scroll scenes are CSS scroll-driven animations (`animation-timeline` with named view timelines), written per section in `<style data-8b-part="scene:...">` blocks. A small inline motion kit at the end of the body numbers items for staggers, measures distances into CSS variables (the collage deal, the week's travel, the ball's roll, the contact run), adds `is-in` to `data-8b-motion` elements as they arrive, pauses endless loops off screen and smooths the mouse wheel (fine pointers only; touch scrolls natively). A gate script in the head sets `data-8b-live` on the root only when the browser supports `animation-timeline` and the visitor has no reduced-motion preference; every scroll rule is scoped to it. The one motion idea is the streak: type and slides slide off or in sideways with a skew, as if they were speeding past. Around it, rings draw and turn, spheres roll and a held track moves sideways.

- **Cover:** on load (CSS keyframes) the frame clips open and the headline lines slide in with a small stagger; the ring turns every 26 seconds and the photo drifts. The cover holds for one screen with CSS `position: sticky`; while it holds, the lines streak off to alternating sides, the photo zooms, the slide shrinks and darkens and the next slide settles in with its heading streaking in and a sphere rolling in from the right.
- **Method:** three round photos roll into gaps in the heading while the words after them slide apart.
- **Sports:** the tiles start as a tilted pile in the middle and are dealt out to their places; each tile's tilt is its inline `--disciplines-tilt`.
- **Coaches:** two rings draw and turn; each portrait settles from a slight zoom (with a blur on wide screens with a mouse).
- **Lab:** a round lens opens on the photo from a small circle, and on wide screens four notes swing around the ring to their `--a` angles; on phones they slide in from the right.
- **Week:** the stage is CSS sticky while the day cards run sideways, with a progress line; a short script leans the track into faster scrolls.
- **Stories to contact:** the quote streaks in, a pale sun sinks into a window, plans rise one by one, a ball rolls down the rail beside the questions, and the contact heading slides along its line.
- **Footer:** the wordmark streaks in from the left.

Streaks last about one second with an exponential ease-out; on hover a button label streaks out and back in over 0.55s. The nav bar hides on a downward scroll past 160px and returns on the way up. With reduced motion, and in browsers without CSS scroll-driven animations (Firefox today), `data-8b-live` is not set: the smooth wheel, streaks, rises, focus settles and all scroll scenes are off, scrolling is the browser's own, the week row scrolls sideways by hand and every section shows its finished layout. The cover's load-in, ring turn and photo drift are CSS keyframes under `prefers-reduced-motion: no-preference`, so they still play in Firefox and stop with reduced motion. Hover effects and the hiding nav bar remain in both cases. If a scene's script throws, the kit logs an error and switches off that scene's styles, so only its section stays static.

## Do's and Don'ts

- Do keep one family, Geist, with weights 400 to 600 only.
- Do keep corners square on slides, photos and fields, and pills only on small controls.
- Do keep the cobalt blue for focus states only.
- Do set a display line's `--len` to its new character count whenever the words change.
- Do keep the gate script, the `data-8b-*` attributes and the inline motion kit; don't add an animation library.
- Do keep the crosshairs and the soft shadow on every new slide.
- Don't add colour photos, gradients in purple or green, or stock icons; photos stay desaturated.
- Don't add rounded cards or heavy shadows.
- Don't use uppercase labels or wide tracking.
- Don't replace the sphere, ring and crosshair graphics with images.
