---
name: The King's Court
colors:
  surface: '#18130a'
  surface-dim: '#18130a'
  surface-bright: '#3f382e'
  surface-container-lowest: '#120d06'
  surface-container-low: '#201b12'
  surface-container: '#251f15'
  surface-container-high: '#2f291f'
  surface-container-highest: '#3b3429'
  on-surface: '#ede1d1'
  on-surface-variant: '#d5c4ad'
  inverse-surface: '#ede1d1'
  inverse-on-surface: '#362f25'
  outline: '#9d8f79'
  outline-variant: '#504533'
  surface-tint: '#ffba29'
  primary: '#ffdca3'
  on-primary: '#422d00'
  primary-container: '#fdb927'
  on-primary-container: '#6c4c00'
  inverse-primary: '#7d5800'
  secondary: '#ddb8ff'
  on-secondary: '#461274'
  secondary-container: '#5e2e8c'
  on-secondary-container: '#d1a1ff'
  tertiary: '#ffd7da'
  on-tertiary: '#5b1725'
  tertiary-container: '#ffb0b8'
  on-tertiary-container: '#863844'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea9'
  primary-fixed-dim: '#ffba29'
  on-primary-fixed: '#271900'
  on-primary-fixed-variant: '#5e4100'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb8ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#5e2e8c'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#ffb2ba'
  on-tertiary-fixed: '#3f0111'
  on-tertiary-fixed-variant: '#792d3a'
  background: '#18130a'
  on-background: '#ede1d1'
  surface-variant: '#3b3429'
typography:
  display-hero:
    fontFamily: Bebas Neue
    fontSize: 120px
    fontWeight: '400'
    lineHeight: 110px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: 0.03em
  headline-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-stats:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-caps:
    fontFamily: Bebas Neue
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 14px
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

This design system is built to honor a legacy of dominance, resilience, and excellence. The brand personality is **authoritative, legendary, and high-octane**. It targets a global audience of sports enthusiasts who demand a premium, "arena-side" digital experience.

The design style is **High-Contrast / Bold** with subtle **Tactile** influences. It utilizes massive, condensed typography to mimic jersey aesthetics and large-scale imagery to convey the physical power of the athlete. Visual interest is driven by high-tension layouts, diagonal structural lines, and background textures inspired by the textures of the game—specifically polished hardwood and pebbled basketball leather. The UI should feel like a premium championship program: heavy, intentional, and undeniable.

## Colors

The palette is a chronological tribute to a historic career, anchored in a **Dark Mode** environment to provide a high-contrast stage for the "Gold" of the present.

- **Primary (Lakers Gold/Purple):** Used for primary actions, highlights, and "Hero" moments. Gold is the lead interactive color.
- **Secondary (Cavs Wine/Navy):** Used for structural depth, background tiers, and historical content sections.
- **Accent (Heat Crimson):** Reserved for high-energy call-outs, live game indicators, and "Heat" streaks.
- **Neutrals:** Deep Black (#0A0A0A) acts as the primary canvas. Concrete Grey is used for utility text and secondary borders to maintain a professional, grounded feel.

Gradients should be used sparingly, primarily as "spotlights" behind player imagery using the secondary colors to create a sense of stadium lighting.

## Typography

The typography strategy is built on a "Power and Precision" model. 

**Headlines** utilize **Bebas Neue**. Its condensed, vertical nature echoes the numbering and lettering found on professional jerseys. Use all-caps for all headline levels to maintain an authoritative tone. 

**Body Text** is set in **Hanken Grotesk**, a clean and highly legible sans-serif that balances the intensity of the headlines with professional refinement. 

**Technical Data and Stats** use **JetBrains Mono**. The monospaced nature of the font ensures that box scores and athletic metrics remain perfectly aligned and easy to scan, providing a technical, analytical layer to the visual narrative.

## Layout & Spacing

This design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is **Dynamic & Asymmetric**. Elements should frequently "break the grid" with slight overlaps or diagonal masking to create a sense of movement.

- **Vertical Rhythm:** Built on an 8px base unit. Section gaps are intentionally large (120px+) to allow the high-scale imagery to breathe.
- **Safe Zones:** Content is contained within a max-width of 1440px, but background textures and atmospheric gradients should bleed to the edge of the viewport.
- **Reflow:** On mobile, large "Display" typography should scale aggressively to ensure it remains the focal point without causing excessive horizontal scrolling.

## Elevation & Depth

Depth is achieved through **Tonal Layering** and **Hard-Edged Shadows**, rather than soft ambient blurs. 

1.  **Base (Level 0):** Deep Black (#0A0A0A) background.
2.  **Court (Level 1):** Subtle leather or hardwood texture overlays with low opacity (5-10%).
3.  **Cards (Level 2):** Use a slightly lighter neutral (e.g., #1A1A1A) with 1px borders in Gold or Purple.
4.  **Interactive (Level 3):** Elements appear to lift using "Hard Shadows"—offsets of 4px or 8px with 100% opacity in the primary Gold color, creating a pop-art or comic-book athletic feel.

Avoid glassmorphism; surfaces should feel solid, opaque, and structural.

## Shapes

The shape language is **geometric and aggressive**. 

A **Soft (0.25rem)** roundedness is applied to cards and containers to prevent the UI from feeling dated or overly "brutalist," but buttons and interactive elements should lean towards sharper corners. 

**The Crown Motif:** Use the crown as a decorative element—either as a container for high-priority avatars (e.g., "The King's Picks") or as a subtle watermark in the corner of premium card components. Diagonal clipped corners (45-degree cuts) can be used on decorative badges or labels to reinforce the athletic aesthetic.

## Components

- **Buttons:** Primary buttons are solid Lakers Gold with Black Bebas Neue text. They use a "thick-border" hover state where a 4px secondary stroke in Purple appears.
- **Stats Chips:** Small, pill-shaped containers using JetBrains Mono. Use the Heat Crimson background for "leading" or "active" stats.
- **News Cards:** Large-scale image backgrounds with a bottom-to-top Black gradient overlay. Headlines are placed at the bottom, left-aligned, using `headline-md`.
- **Inputs:** Dark backgrounds with a 1px Concrete Grey bottom-border only. When focused, the border transitions to a 2px Lakers Gold stroke.
- **Lists:** Used for box scores. Alternate row colors between Deep Black and a very dark Navy Blue (#041E42) to maintain legibility in dense data.
- **The "Legacy" Timeline:** A vertical line component using a Gold-to-Wine gradient, with circular nodes representing key career milestones.