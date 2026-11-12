# AI: Dynamic Web Lab Generation for Core CSS Concepts

Single-file HTML/CSS/JS labs generated with sequential AI prompting to visualize core CSS concepts.

**AI tool used:** [add the tool you used, e.g. Gemini with Canvas]

## Files
| File | Description |
|---|---|
| `box-model-lab-v1-initial.html` | Initial Box Model & Display lab: Box 1 and Box 2, sliders for padding, margin, border-width and width, display dropdown (block, inline-block, inline), live pixel labels, colored content/padding/margin areas. |
| `box-model-lab-v2-refined.html` | Refined lab: per-side (top, right, bottom, left) margin, padding and border sliders plus a corner radius slider. |
| `flexbox-grid-playground.html` | Flexbox/Grid playground: container with 5 items and dropdowns for display, flex-direction, justify-content, align-items and grid-template-columns, updating in real time. |

## Prompts
1. **Initial:** Box Model & Display lab prompt (see submission document).
2. **Refinement:** "Implement sliders to adjust the margin, padding, and border for each side (top, right, bottom, left) individually, and add a separate slider for the corner radius."
3. **Flexbox/Grid:** playground prompt (see submission document).

## How to run
Open any `.html` file in a browser. No build step or dependencies.

## Key learning
Sequential prompting gave a tested baseline first, then one scoped change, which made bugs easy to trace, much like incremental commits in real development.
