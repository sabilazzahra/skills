# Stacks

## React
- Build reusable primitives with explicit state props.
- Keep component APIs predictable and token-driven.
- Separate presentational components from business containers.

## Next.js
- Distinguish marketing, app shell, and dashboard routes early.
- Account for SSR, loading states, and route transitions in design specs.
- Specify empty/loading/error states for streaming or async data.

## Vue
- Design for slot-based composition and prop clarity.
- Use controlled variants for common enterprise patterns.

## Tailwind
- Translate spacing, radius, shadows, and color roles into tokens/utilities.
- Avoid one-off arbitrary values unless they are becoming tokens.

## shadcn/ui
- Start from accessible base components, then extend with product-specific variants.
- Document where default patterns should be overridden for density or branding.

## HTML/CSS
- Preserve semantic structure, not just appearance.
- Use layout primitives that degrade gracefully: grid, flex, container queries when available.

## Figma
- Define component properties, variants, and naming before scaling.
- Use auto layout by default for app UI.
- Mirror engineering tokens in variables/styles where practical.
- Prepare dev handoff with states, spacing logic, and usage notes.
