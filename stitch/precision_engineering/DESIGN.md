# Design System Specification: Kinetic Precision

## 1. Overview & Creative North Star
The Creative North Star for this design system is **"Kinetic Precision."** 

In the world of automotive E/E (Electrical/Electronic) engineering, the intersection of massive complexity and absolute accuracy is where innovation lives. This system moves away from the "boxy" nature of standard B2B SaaS. Instead, it adopts an editorial, high-performance aesthetic that mirrors the fluidity of electrical currents and the rigid discipline of engineering schematics. 

We break the "template" look through:
*   **Intentional Asymmetry:** Using whitespace as a structural element to guide the eye toward technical breakthroughs.
*   **Tonal Depth:** Replacing harsh outlines with layered, translucent surfaces.
*   **Sophisticated Scale:** Drastic contrast between oversized display type and micro-monospaced technical data.

## 2. Colors
Our palette is rooted in a deep, authoritative Navy (`on_surface`) and elevated by a "Signal Flow" gradient that represents the movement of data.

*   **The Blue-Teal Gradient:** Utilize a linear gradient from `primary_container` (#1A73E8) to `secondary` (#006a61). This is reserved for high-impact moments: primary CTAs, active data paths, and hero accents.
*   **The "No-Line" Rule:** Standard 1px solid borders are strictly prohibited for sectioning. Boundaries must be defined through background color shifts. For example, a `surface_container_low` (#f2f3ff) section should sit directly against a `surface` (#faf8ff) background to create a sophisticated, borderless transition.
*   **Surface Hierarchy & Nesting:** Treat the UI as physical layers of frosted glass. 
    *   Base: `surface`
    *   Sectioning: `surface_container_low`
    *   Interactive Components: `surface_container` or `surface_container_highest`
*   **Signature Textures:** Use the `primary` (#005bbf) color at 5% opacity as a subtle wash over large `surface` areas to provide a "cool" professional tint that feels more bespoke than flat white.

## 3. Typography
The typography strategy creates a dialogue between "The Vision" (Display) and "The Machine" (Technical).

*   **Display & Headlines (Inter):** Used for narrative-driven moments. The `display-lg` (3.5rem) should feel massive and authoritative, with tight letter-spacing (-0.02em) to mimic high-end editorial layouts.
*   **Body (Manrope):** The `body-lg` (1rem) provides a modern, readable rhythm. It is the "human" element of the platform.
*   **Technical Labels (Space Grotesk):** This is our "Precision" font. Use `label-md` and `label-sm` for technical data, chip labels, and monospace-adjacent details. This conveys the E/E engineering heritage.

## 4. Elevation & Depth
Depth is achieved through **Tonal Layering** rather than traditional drop shadows.

*   **The Layering Principle:** To lift an element (like a card), place a `surface_container_lowest` (#ffffff) object onto a `surface_container` (#eaedff) background. The contrast in tone provides the "lift."
*   **Ambient Shadows:** If a floating element (like a dropdown) requires a shadow, it must be an "Ambient Shadow": `0px 24px 48px rgba(11, 17, 32, 0.06)`. The tint is derived from our Dark Navy `on_surface`, making the shadow feel like a natural light obstruction rather than a UI artifact.
*   **The "Ghost Border" Fallback:** If a container requires a border for accessibility, use the `outline_variant` (#c1c6d6) at 20% opacity. It should be barely perceptible.
*   **Glassmorphism:** For floating navigation or sidebars, use `surface` with 80% opacity and a `20px` backdrop-blur. This allows the engineering "schematics" in the background to bleed through, maintaining a sense of technical depth.

## 5. Components

### Buttons
*   **Primary:** A "Kinetic" gradient from `primary_container` to `secondary`. Use `rounded-md` (0.375rem). Text should be `label-md` in `on_primary`.
*   **Secondary:** `surface_container_highest` background with `on_surface` text. No border.
*   **Tertiary/Ghost:** Transparent background, `on_surface_variant` text, with a `primary` underline appearing only on hover.

### Cards & Containers
*   **Strict Rule:** No dividers. Use vertical whitespace (32px or 48px from the spacing scale) to separate content blocks. 
*   **Styling:** Use `surface_container_lowest` for card backgrounds on a `surface_container_low` page. Apply `rounded-xl` (0.75rem).

### Technical Chips
*   **Style:** Small, `label-sm` type. Background: `surface_variant`. 
*   **Accent Chips:** For status (e.g., "Active Signal"), use `secondary_container` with `on_secondary_container` text.

### Input Fields
*   **State:** Default state uses `surface_container_high` with no border. 
*   **Focus State:** A 1px "Ghost Border" using `primary` at 40% and a subtle `primary_fixed` glow.

### Automotive-Specific Components
*   **The Schematic Node:** A specialized card using `surface_dim` for the header and `surface_container_lowest` for the body, connected by "Signal Lines" (2px strokes using the `primary_container` to `secondary` gradient).

## 6. Do's and Don'ts

### Do:
*   **Embrace Whitespace:** If a section feels crowded, double the padding. Engineering precision requires room to breathe.
*   **Align to the Grid, then Break it:** Place technical metadata (Monospace) slightly off-axis from the main headline to create a "blueprint" feel.
*   **Use Subtle Animation:** When hovering over a "Kinetic" element, use a 400ms `cubic-bezier(0.23, 1, 0.32, 1)` transition for the gradient shift.

### Don't:
*   **Don't use 100% Black:** Always use `on_surface` (#151b2b) for text to maintain the premium navy undertone.
*   **Don't use Heavy Borders:** If you feel the need for a border, use a background color shift instead.
*   **Don't use Generic Icons:** Use ultra-thin (1pt) stroke icons that match the `outline` token. Never use filled, "bubbly" icons.