---
name: Industrial Integrity
colors:
  surface: '#f6faff'
  surface-dim: '#d6dae0'
  surface-bright: '#f6faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4fa'
  surface-container: '#eaeef4'
  surface-container-high: '#e4e8ef'
  surface-container-highest: '#dfe3e9'
  on-surface: '#171c20'
  on-surface-variant: '#424751'
  inverse-surface: '#2c3136'
  inverse-on-surface: '#edf1f7'
  outline: '#727782'
  outline-variant: '#c2c6d2'
  surface-tint: '#255fa6'
  primary: '#003469'
  on-primary: '#ffffff'
  primary-container: '#004b91'
  on-primary-container: '#95bdff'
  inverse-primary: '#a7c8ff'
  secondary: '#5b5f60'
  on-secondary: '#ffffff'
  secondary-container: '#dde0e1'
  on-secondary-container: '#5f6364'
  tertiary: '#003c37'
  on-tertiary: '#ffffff'
  tertiary-container: '#00554f'
  on-tertiary-container: '#4bcfc2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#004689'
  secondary-fixed: '#e0e3e4'
  secondary-fixed-dim: '#c4c7c8'
  on-secondary-fixed: '#181c1d'
  on-secondary-fixed-variant: '#434748'
  tertiary-fixed: '#78f7e9'
  tertiary-fixed-dim: '#59dacd'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#00504a'
  background: '#f6faff'
  on-background: '#171c20'
  surface-variant: '#dfe3e9'
  posco-blue: '#004B91'
  steel-gray: '#70757A'
  sustainability-cyan: '#00A99D'
  deep-navy: '#002F56'
  surface-alt: '#F8FAFB'
typography:
  display-lg:
    fontFamily: notoSans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: notoSans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: notoSans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: notoSans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: notoSans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: notoSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: notoSans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: notoSans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  container-max: 1440px
---

## Brand & Style

This design system is engineered for a global B2B industrial leader, balancing the monumental strength of steel production with the precision of future-oriented technology. The brand personality is authoritative, reliable, and visionary.

The aesthetic follows a **Corporate / Modern** direction with a focus on high-density information management and structural clarity. Drawing inspiration from the organized modularity of premium portals, the design prioritizes high-quality industrial photography and generous whitespace to create a sense of scale and transparency. The visual tone is "Heavy industry meets High-tech," utilizing clean lines and a disciplined grid to convey stability and ESG-driven innovation.

## Colors

The color strategy is anchored by **POSCO Blue**, representing trust and the heritage of the steel industry. This is supported by a spectrum of **Steel Grays** that provide a sophisticated, neutral backdrop for complex data and industrial imagery.

To emphasize the commitment to ESG and future energy, a vibrant **Sustainability Cyan** is used as an accent color for highlights, progress indicators, and eco-friendly initiatives. The interface primarily uses a light mode to maintain a clean, professional atmosphere, utilizing subtle off-whites (`#F4F7F8`) for section zoning to reduce eye strain during prolonged use.

## Typography

The typography system utilizes **Noto Sans**, providing a highly legible, neutral, and professional character that supports multi-language B2B communication. 

Hierarchy is established through significant weight shifts rather than excessive size changes. Headlines are bold and tightly tracked to evoke the strength of steel, while body text maintains a generous line height for maximum readability in technical reports and data-heavy interfaces. Label styles use increased letter spacing and uppercase transforms for secondary metadata to distinguish them clearly from prose.

## Layout & Spacing

The layout employs a **12-column fluid grid** for desktop, transitioning to 8 columns for tablet and 4 columns for mobile. Content is housed within a maximum container width of 1440px to ensure readability on ultra-wide monitors.

The spacing rhythm is based on an 8px square grid. Large sections should be separated by 80px to 120px of vertical whitespace to maintain a premium, organized feel similar to high-end corporate portals. Internal component padding should remain consistent at 16px or 24px increments to reinforce the "built" and "structured" nature of the industrial brand.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows to convey depth. This approach reflects the precision of engineering.

- **Level 0 (Base):** Standard background color (`#FFFFFF`).
- **Level 1 (Zoning):** Subtle background shifts (`#F4F7F8`) used to group related content blocks or sidebar menus.
- **Level 2 (Interactive):** Elements like cards or dropdowns use a 1px border (`#E1E4E8`) and an extremely soft, large-radius ambient shadow (5% opacity) to suggest they are "resting" on the surface.
- **Level 3 (Modals):** Focused elements use a 15% opacity neutral shadow with 0px offset to create a clean "lift" from the page without looking decorative.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding provides a modern touch that prevents the UI from feeling dated or overly aggressive, while still maintaining the architectural rigidity expected of a global industrial leader. Large containers or featured imagery should never exceed 0.75rem corner radii to maintain a professional, high-end corporate aesthetic.

## Components

### Buttons
Primary buttons utilize the **POSCO Blue** with white text, featuring sharp but slightly softened corners. Secondary buttons should use a ghost style with a 1px steel-gray border. Hover states should involve a subtle shift to **Deep Navy** to indicate weight and solidity.

### Cards
Cards are the primary container for information. They feature a white background, a 1px light gray border, and no shadow in their default state. On hover, a card may exhibit a very soft ambient shadow and a 2px top-border accent in **Sustainability Cyan**.

### Input Fields
Fields are designed for data precision. They use a solid 1px border in a medium-gray, which shifts to **POSCO Blue** on focus. Labels sit clearly above the field in a bold, smaller typeface.

### Chips & Badges
Used primarily for ESG categories or status updates (e.g., "Carbon Neutral," "In Production"). These should be rectangular with the smallest radius (0.25rem), using desaturated background tints of the brand colors with high-contrast text.

### Industrial Data Lists
Tables and lists should use alternating row highlights (`#F8FAFB`) and clear dividers. Priority is given to column alignment and typographic hierarchy to make complex technical specs easy to scan.