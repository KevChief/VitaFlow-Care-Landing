# VitaFlow - Design System & Brand Guidelines v1.0

**Core Principles:** Seamless, Trustworthy, Modern, Patient-Centric, Scalable

*This document serves as the single source of truth for the visual and interactive design of the VitaFlow application, encompassing mobile apps for patients and a web platform for practitioners. All components and screens must adhere to these guidelines to ensure a consistent, high-quality user experience across platforms, aligned with GDPR compliance and Benelux healthcare standards.*

---

## 1. Color Palette

The color system reflects VitaFlow’s “Vital Flow” ethos, with a focus on health, trust, and fluidity. Two themes are supported: **Vital Dark** and **Vital Light**, switchable based on user preference or system settings (e.g., for practitioner dashboards or patient apps).

*Each color includes a visual preview derived from the provided SVG logos.*

### 1.1. Shared Colors

These colors maintain brand consistency across both themes, inspired by the logo’s green (#6CE9A6) and blue (#5FE8D5).

#### Accent Colors

| Preview | Name | Description | Hex | Usage |
|---------|------|-------------|-----|-------|
| ![Vital Green](https://placehold.co/15x15/6CE9A6/6CE9A6.png) | `primaryAccent` | Vital Green | `#6CE9A6` | Buttons, progress bars, active states, highlights. Represents vitality and health. |
| ![Flow Blue](https://placehold.co/15x15/5FE8D5/5FE8D5.png) | `secondaryAccent` | Flow Blue | `#5FE8D5` | (Use Sparingly) Subtle highlights, notifications, flow indicators (e.g., calendar sync progress). |

#### System Colors

| Preview | Name | Description | Hex | Usage |
|---------|------|-------------|-----|-------|
| ![Success Green](https://placehold.co/15x15/6CE9A6/6CE9A6.png) | `success` | Success Green | `#6CE9A6` | Positive feedback (e.g., booking confirmation), patient satisfaction indicators. |
| ![Alert Orange](https://placehold.co/15x15/FDB022/FDB022.png) | `warning` | Alert Orange | `#FDB022` | Gentle alerts (e.g., waitlist nearing capacity), no-show risk notifications. |
| ![Error Red](https://placehold.co/15x15/F04438/F04438.png) | `error` | Error Red | `#F04438` | Error messages, destructive actions (e.g., canceling a booked slot). |

---

### 1.2. Theme: Vital Dark

Designed for focused use in low-light environments, ideal for practitioner night shifts.

| Preview | Name | Description | Hex | Usage |
|---------|------|-------------|-----|-------|
| ![Deep Midnight](https://placehold.co/15x15/101828/101828.png) | `darkBackground` | Deep Midnight | `#101828` | Main app/web background. |
| ![Slate Blue](https://placehold.co/15x15/1D2939/1D2939.png) | `darkSurface` | Slate Blue | `#1D2939` | Cards, modals, elevated surfaces. |
| ![Soft White](https://placehold.co/15x15/F2F4F7/F2F4F7.png) | `darkTextPrimary` | Soft White | `#F2F4F7` | Main headings, body text. |
| ![Grey Mist](https://placehold.co/15x15/98A2B3/98A2B3.png) | `darkTextSecondary` | Grey Mist | `#98A2B3` | Subtitles, disabled text, placeholders. |
| ![Dark Steel](https://placehold.co/15x15/344054/344054.png) | `darkBorder` | Dark Steel | `#344054` | Subtle dividers, component borders. |

### 1.3. Theme: Vital Light

A bright, clean theme for daytime use, enhancing patient app readability.

| Preview | Name | Description | Hex | Usage |
|---------|------|-------------|-----|-------|
| ![Light Mist](https://placehold.co/15x15/F2F4F7/F2F4F7.png) | `lightBackground` | Light Mist | `#F2F4F7` | Main app/web background. |
| ![Pure Glow](https://placehold.co/15x15/FFFFFF/FFFFFF.png) | `lightSurface` | Pure Glow | `#FFFFFF` | Cards, modals, elevated surfaces. |
| ![Deep Slate](https://placehold.co/15x15/101828/101828.png) | `lightTextPrimary` | Deep Slate | `#101828` | Main headings, body text. |
| ![Cool Grey](https://placehold.co/15x15/667085/667085.png) | `lightTextSecondary` | Cool Grey | `#667085` | Subtitles, disabled text, placeholders. |
| ![Light Silver](https://placehold.co/15x15/D0D5DD/D0D5DD.png) | `lightBorder` | Light Silver | `#D0D5DD` | Subtle dividers, component borders. |

---

## 2. Typography

A two-font system ensures a clear hierarchy, sourced from Google Fonts, tailored for healthcare readability.

- **Headings Font:** `Montserrat` (Bold, professional for practitioner dashboards).
- **Body/UI Font:** `Poppins` (Friendly, legible for patient apps).

### 2.1. Type Scale

| Name         | Font Family         | Weight     | Size  | Letter Spacing |
|--------------|---------------------|------------|-------|----------------|
| `headline1`  | Montserrat          | Bold       | 32pt  | -0.5           |
| `headline2`  | Montserrat          | SemiBold   | 24pt  | 0.0            |
| `headline3`  | Montserrat          | Regular    | 20pt  | 0.0            |
| `bodyLarge`  | Poppins             | Regular    | 18pt  | 0.25           |
| `body`       | Poppins             | Regular    | 16pt  | 0.5            |
| `caption`    | Poppins             | Light      | 14pt  | 0.4            |
| `button`     | Poppins             | Medium     | 16pt  | 1.25           |

---

## 3. Layout & Spacing

A consistent 8-point grid ensures a harmonious layout across mobile and web.

- **Core Principle:** **8-Point Grid System**
- **Rule:** All margins, padding, and positional values must be multiples of 8 (e.g., `8`, `16`, `24`, `32`, `40`).

### 3.1. Spacing Tokens

| Name      | Value | Usage                                      |
|-----------|-------|--------------------------------------------|
| `spacing-xs` | `8px` | Small gaps (e.g., between form fields).    |
| `spacing-s`  | `16px`| Standard padding (e.g., inside cards, buttons). |
| `spacing-m`  | `24px`| Gaps between components (e.g., booking slots). |
| `spacing-l`  | `32px`| Gaps between sections (e.g., dashboard panels). |
| `spacing-xl` | `48px`| Large padding (e.g., screen-level containers). |

---

## 4. Components & UI Elements

### 4.1. Iconography
- **Library:** **Material Symbols**
- **Variant:** **Outlined**
- **Rule:** Use healthcare-relevant icons (e.g., calendar, user, checkmark) from this set for consistency.

### 4.2. Borders & Corner Radius
- **Standard Corner Radius:** `12px` (for cards, inputs, buttons).
- **Large Corner Radius:** `16px` (for modals, pop-ups).
- **Full/Pill Radius:** `999px` (for circular progress indicators).
- **Border Width:** `1px`
- **Border Color:** Use `darkBorder` or `lightBorder` based on theme.

### 4.3. Buttons
- **Primary Button:** Solid `primaryAccent` background, `darkTextPrimary`/`lightTextPrimary` text.
- **Secondary Button:** Outlined with `secondaryAccent` border, `secondaryAccent` text.
- **Text Button:** No background/border, `secondaryAccent` text.

---

## 5. Animation & Motion

Subtle, fast animations enhance usability and reflect the “flow” theme.

- **Duration:** `150ms` - `250ms` for UI animations.
- **Easing:** `ease-out` for responsive feel.

### 5.1. Key Animations
- **Booking Confirmation:**
  - **Trigger:** Slot booked.
  - **Animation:** Checkmark draws in, subtle `primaryAccent` wave pulses outward, fades in `200ms`.
- **Waitlist Update:**
  - **Trigger:** Waitlist slot opens.
  - **Animation:** Slot highlights with `secondaryAccent` glow, slides up, fades out in `250ms`.
- **Screen Transitions:**
  - **Default:** Fade-in/fade-out (`200ms`).
  - **Modals:** Slide up from bottom (`250ms`).

---

## 6. Accessibility
- **Color Contrast:** Minimum WCAG AA contrast (e.g., `darkTextPrimary` on `darkBackground`). Use a contrast checker during design/dev.
- **Tap Targets:** Minimum `44x44` logical pixels for buttons/icons (critical for patient app usability).
- **Semantics:** Descriptive labels for screen readers (e.g., VoiceOver, TalkBack) on all interactive elements (e.g., “Book Appointment Button”).

---