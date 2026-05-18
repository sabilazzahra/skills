# Rule Categories

Priority table from 1–10 to decide how hard to enforce a rule.

| Priority | Impact | Domain | Key checks | Anti-patterns |
|---|---|---|---|---|
| 1 | Critical | Accessibility | Contrast, focus, keyboard, semantics | Hidden focus, color-only meaning |
| 2 | Critical | Error Prevention | Validation, confirmation, recovery | Silent failure, irreversible taps |
| 3 | High | Core Task Flow | Navigation, task completion, context retention | Dead ends, context resets |
| 4 | High | Data Accuracy | Tables, charts, units, freshness | Ambiguous numbers, misleading scales |
| 5 | High | Status & Feedback | Loading, success, error, async jobs | No feedback, vague toasts |
| 6 | Medium-High | Readability | Typography, spacing, hierarchy | Tiny text, weak contrast, clutter |
| 7 | Medium | Consistency | Components, tokens, naming | One-off styles, mixed patterns |
| 8 | Medium | Theme Integrity | Light/dark parity, semantic tokens | Dark mode afterthoughts |
| 9 | Medium-Low | Motion & Polish | Transition clarity, reduced motion | Decorative motion everywhere |
| 10 | Situational | Brand Expression | Style uniqueness, delight moments | Style over usability |

## Use
- Fix priority 1–4 issues before visual polish debates.
- Let priority 5–8 shape system quality and delivery confidence.
- Treat priority 9–10 as optional when deadlines are tight unless brand differentiation is the goal.
