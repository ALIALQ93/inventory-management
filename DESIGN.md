---
name: Premium Enterprise Inventory
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#43474c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#74777d'
  outline-variant: '#c4c6cd'
  surface-tint: '#4e6073'
  primary: '#162839'
  on-primary: '#ffffff'
  primary-container: '#2c3e50'
  on-primary-container: '#96a9be'
  inverse-primary: '#b5c8df'
  secondary: '#4b6076'
  on-secondary: '#ffffff'
  secondary-container: '#cce2fc'
  on-secondary-container: '#50657b'
  tertiary: '#002b36'
  on-tertiary: '#ffffff'
  tertiary-container: '#004252'
  on-tertiary-container: '#00b5dd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4fb'
  primary-fixed-dim: '#b5c8df'
  on-primary-fixed: '#091d2e'
  on-primary-fixed-variant: '#36485b'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#b3c9e2'
  on-secondary-fixed: '#051d30'
  on-secondary-fixed-variant: '#34495e'
  tertiary-fixed: '#b7eaff'
  tertiary-fixed-dim: '#4cd6ff'
  on-tertiary-fixed: '#001f28'
  on-tertiary-fixed-variant: '#004e60'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  emerald-action: '#10B981'
  surface-white: '#FFFFFF'
  border-subtle: '#E2E8F0'
  text-muted: '#64748B'
typography:
  headline-xl:
    fontFamily: manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
  headline-md:
    fontFamily: manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: beVietnamPro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: beVietnamPro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  body-sm:
    fontFamily: beVietnamPro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: beVietnamPro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-margin: 24px
  gutter: 16px
  card-padding: 20px
  section-gap: 32px
---

## Brand & Style

The design system is engineered for **RoseMary Software Solutions** to embody a "Premium Enterprise" personality. It balances the high-stakes reliability of logistics management with a forward-thinking tech aesthetic. The target audience includes warehouse managers, inventory controllers, and administrative executives who require high information density without sacrificing clarity or aesthetic appeal.

The chosen style is **Corporate Modern**, characterized by:
- **Professional Precision:** A focus on alignment and structured data presentation.
- **Subtle Depth:** Using soft elevation rather than flat aesthetics to guide the user’s eye through complex workflows.
- **Tech-Forward Accents:** Infusing classic corporate tones with vibrant, high-energy interactive elements to signify modern software capabilities.

## Colors

The palette is anchored by **Deep Navy (#2C3E50)** and **Professional Slate (#34495E)**, providing a stable, authoritative foundation for navigation and headers. These colors evoke trust and permanence.

The primary action color is an **Electric Blue (#00D1FF)**, used for critical path interactions like "Add New" or "Submit." For success states and specific inventory actions, an **Emerald Green (#10B981)** is utilized to provide high-contrast feedback. Surfaces rely on a clean **White (#FFFFFF)** background with **Light Gray (#F5F5F5)** sectioning to create a logical separation of concerns without the visual clutter of heavy borders.

## Typography

This design system uses a dual-font approach to ensure clarity in both Arabic and English. **Manrope** is used for headlines to provide a modern, geometric, and authoritative structure. It scales beautifully from large dashboard titles to section headers.

**Be Vietnam Pro** is selected for body text and labels. Its slightly wider apertures and contemporary humanist traits ensure that dense inventory lists and data tables remain legible on mobile and desktop screens alike. 

- **Hierarchical Scale:** Maintain a strict contrast between labels (SemiBold) and data values (Regular).
- **RTL Optimization:** When rendering Arabic, line heights are increased by 15% to accommodate script descenders and accents without crowding the interface.

## Layout & Spacing

The system follows a **Fixed-Fluid Hybrid** grid. On desktop, content is contained within a max-width of 1440px to prevent excessive scanning strain, while dashboard elements utilize a 12-column fluid grid within that container.

**Breakpoints:**
- **Mobile (< 768px):** 4-column grid. Tables reflow into "List Cards" where each row becomes a standalone card with stacked key-value pairs.
- **Tablet (768px - 1024px):** 8-column grid. Sidebar collapses into a compact icon-only rail.
- **Desktop (> 1024px):** 12-column grid. Full persistent navigation.

Spacing is based on an **8px base unit**, ensuring consistent rhythm. Sectioning is achieved through varying background shades (`neutral-color`) rather than explicit line dividers where possible.

## Elevation & Depth

To maintain a "Professional & Sophisticated" feel, this design system avoids heavy, dark shadows. Instead, it utilizes **Ambient Tonal Elevation**:

- **Level 0 (Background):** Solid `#F5F5F5`.
- **Level 1 (Cards/Tables):** Solid White with a 1px border of `#E2E8F0` and a very soft, diffused shadow (`0 4px 12px rgba(44, 62, 80, 0.05)`).
- **Level 2 (Modals/Dropdowns):** Elevated with a more pronounced shadow to indicate interactivity (`0 12px 32px rgba(44, 62, 80, 0.12)`).

Depth is further communicated through **Tonal Layering**, where the navigation sidebar is a darker tone (`primary-color`) than the main work surface, visually pushing the content forward.

## Shapes

The shape language is defined by **Soft Roundedness**. All standard interactive elements (buttons, inputs, cards) use a **12px - 16px corner radius** (defined as `rounded-lg` in the tokens). 

This rounding serves to soften the "industrial" nature of inventory software, making the tool feel more approachable and modern.
- **Buttons & Inputs:** 12px (Soft).
- **Dashboard Stats Cards:** 16px (Rounded).
- **Status Pills:** Fully pill-shaped for immediate distinction from actionable buttons.

## Components

### Buttons
- **Primary:** Solid `#00D1FF` with white text. High-contrast, 12px radius.
- **Secondary:** Outlined `#2C3E50` with 1.5px stroke.
- **Success/Action:** Solid `#10B981` (Emerald) for "Save" or "Confirm" actions.

### Dashboard Stats Cards
- Background: White.
- Border-left: 4px solid `#00D1FF` to provide a color-coded category accent.
- Content: Large `headline-md` for the metric, `label-md` for the title.

### Data Tables (Mobile-Optimized)
- **Desktop:** Compact rows (48px height) with subtle hover states.
- **Mobile:** Tables transform into cards. The "Header" row is hidden, and each cell is prefixed with its label in a muted, bold font (`text-muted`).

### Form Fields
- **Inputs:** White background, 12px radius, `#E2E8F0` border.
- **Active State:** Border transitions to `#00D1FF` with a 2px outer glow of the same color at 10% opacity.
- **Labels:** Positioned above the field in `label-md`.

### Status Indicators
- Use a small colored dot next to text (e.g., Active = Green, Out of Stock = Red) to maintain high legibility and accessibility.