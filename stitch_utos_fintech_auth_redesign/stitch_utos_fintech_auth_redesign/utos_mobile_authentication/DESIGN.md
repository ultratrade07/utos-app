---
name: UTOS Mobile Authentication
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eefe'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce2f3'
  on-surface: '#151c27'
  on-surface-variant: '#444748'
  inverse-surface: '#2a313d'
  inverse-on-surface: '#ebf1ff'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002113'
  on-tertiary-container: '#009668'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce2f3'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system establishes a high-trust, frictionless onboarding and authentication environment for modern mobile fintech. Rooted in minimalist precision and quiet confidence, it projects institutional reliability combined with consumer-grade software elegance. 

The aesthetic is clean, spacious, and tactile without resorting to skeuomorphism. It balances soft, warm architectural grays with crisp pure-white surfaces, high-contrast dark typography, and disciplined strokes of electric blue. Visual hierarchy is established through meticulous spatial pacing and typographic contrast rather than heavy ornament or theatrical drop shadows. The emotional tone is calm, reassuring, and secure—eliminating cognitive friction during sensitive credential entry, biometric verification, and two-factor challenges.

## Colors
The palette operates with strict functional restraint to minimize distraction and prioritize data clarity:

- **Canvas & Background (`#F7F8FA`):** An ultra-soft, low-saturation gray canvas that eliminates glare while providing adequate contrast against foreground surfaces.
- **Surface Cards & Inputs (`#FFFFFF`):** Pure white container surfaces that ground interactive fields and cards over the soft gray canvas.
- **Primary Accent (`#111111`):** Deep carbon black reserved for high-priority elements, primary CTAs, active segmented pill controls, and authoritative branding anchors.
- **Brand Accent (`#2563EB`):** A vivid cobalt blue reserved for hyper-contextual interactions—inline text links, active input focus rings, radio selections, biometric badges, and active switch toggles.
- **Secondary Neutral (`#6B7280`):** Neutral slate for secondary descriptions, hints, captions, and inactive iconography.
- **Muted Neutral (`#9CA3AF`):** Subdued gray for input placeholders, deactivated states, and subtle dividers.
- **Borders & Dividers (`#E5E7EB`):** Precise 1px structural outlines that define boundaries without introducing visual clutter.
- **Semantic Feedback:** Positive verification states use Emerald Green (`#10B981`); security errors or invalid credential alerts utilize Crimson Red (`#EF4444`).

## Typography
Plus Jakarta Sans provides geometric clarity with humanized softness, optimal for rapid scannability on high-density mobile screens. 

- **Headlines:** Set with tight tracking (`-0.02em` to `-0.01em`) and semibold to bold weights, maintaining an authoritative and confident presence across authentication prompts, pin entry requests, and welcome screens.
- **Body:** Calibrated line heights (1.4–1.5x) prevent eye fatigue during reading of disclaimers, Terms of Service excerpts, or contextual verification instructions.
- **Numeric Fields & PINs:** Numerals in authentication OTP fields adopt tabular lining figures (`font-variant-numeric: tabular-nums`) to ensure absolute alignment without optical jitter.

## Layout & Spacing
The layout system is tailored for one-handed mobile ergonomic zones, built on a unified 4px base module (implemented via the 8px spatial grid).

- **Mobile Viewport Grid:** Utilizes a fluid 4-column column system on mobile screens with `1.25rem` (20px) outer canvas margins, transitioning to a centered 400px–440px constrained card column for tablet and desktop viewports.
- **Vertical Rhythm:** Auth views are divided into three ergonomic strata:
  1. *Header Zone:* Progress bars, back triggers, and screen titles top-anchored with generous clearance for mobile status bars (`env(safe-area-inset-top)` + `1.5rem`).
  2. *Interactive Core:* Centered form fields, OTP pins, and contextual helper text.
  3. *Action Anchor:* Bottom-pinned primary actions, persistent biometric shortcuts, and legal microcopy placed above the home indicator (`env(safe-area-inset-bottom)` + `1rem`).
- **Touch Ergonomics:** Interactive targets never drop below 48px height, standardizing on 52px–56px for primary CTA buttons and form inputs.

## Elevation & Depth
This design system avoids heavy drop shadows and dramatic skeuomorphic depth. Visual hierarchy is achieved through crisp planar layering and hairline boundaries:

- **Surface Layering:** The primary canvas sits at `#F7F8FA`. Card groupings, modal sheets, and floating inputs rest at pure `#FFFFFF`.
- **Low-Contrast Outlines:** Surfaces and inputs are framed with a precise 1px border in `#E5E7EB`.
- **Ambient Micro-Elevation:** Where separation is mandatory (e.g., sticky action footers or slide-up authentication sheets), an ultra-diffused, tinted shadow is applied: `0px 8px 24px rgba(17, 24, 39, 0.04)`.
- **Active Focus Rings:** When an input receives focus, the standard border transitions to an assertive `#2563EB` stroke paired with a subtle, non-blurry outer ring: `box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.12)`.

## Shapes
The shape language implements a modern pill/squircle geometry that softens touchpoints and feels natural under thumb interaction:

- **Inputs and Primary CTAs:** Standardized with full pill or soft squircle radius (16px to 28px / full pill), reinforcing physical affordance and comfortable tapping targets.
- **Card Enclosures & Verification Modals:** Built with a continuous `rounded-xl` corner radius (24px to 28px) to frame multi-step forms securely.
- **Badges, Pills & Indicators:** Full pill curvature (`9999px`) applied to segmented mode switches, status pills, and biometric glyph surrounds.

## Components

### Primary & Secondary Buttons
- **Primary CTA:** Height 54px, full pill radius (`9999px`), solid `#111111` background, `#FFFFFF` typography (`label-lg`). Under active press: transitions smoothly to `#262626` with a scale transform of `0.985`.
- **Secondary / Outlined:** Height 54px, 1px border `#E5E7EB`, `#FFFFFF` background, `#111827` typography. Active press yields `#F7F8FA`.
- **Ghost / Text Button:** Zero border, transparent fill, `#2563EB` text (`label-md`), used for "Forgot Password?", "Resend OTP", or "Skip".

### Form Inputs & Text Fields
- **Container:** Height 54px, 1px solid border `#E5E7EB`, background `#FFFFFF`, border-radius 16px. Padding inline 16px.
- **Typography:** Value text in `#111827` (`body-lg`), placeholder text in `#9CA3AF`.
- **Floating Labels:** Positioned above the field in `#6B7280` (`label-sm`).
- **Focus State:** Border shifts to `#2563EB` accompanied by a 3px soft accent ring (`rgba(37, 99, 235, 0.12)`).
- **Trailing Accessories:** 20px monochrome icons (`#6B7280`) for password reveal toggles, input clearance, or biometric status glyphs.

### One-Time Password (OTP) / PIN Blocks
- Set of 4 or 6 discrete square-rounded modules (height 56px, width 48px), border-radius 14px, background `#FFFFFF`, border 1px solid `#E5E7EB`.
- Active focused cell displays a 2px `#2563EB` border. Completed entries render large, bold numerical glyphs (`headline-md`).

### Biometric Auth Trigger
- Dedicated 54px secondary button or 56px circular module hosting a clean 24px FaceID/fingerprint icon in `#111111`, set against `#FFFFFF` with a 1px border in `#E5E7EB`.

### Toggle Switches & Selection Controls
- **Switch:** Track dimensions 48px × 28px, rounded pill, inactive background `#E5E7EB`, active background `#2563EB`. Thumb is 24px pure `#FFFFFF` circle with 2px offset.
- **Checkbox & Radio:** 20px dimensions, 1.5px border `#D1D5DB`. When checked: fills with `#2563EB` displaying a crisp white micro-checkmark or center radio dot.

### Cards & Container Panels
- White `#FFFFFF` structural containers, 1px solid border `#E5E7EB`, border-radius 24px, inner padding `1.5rem` (24px). Shadows are excluded in favor of surface contrast against the `#F7F8FA` canvas.