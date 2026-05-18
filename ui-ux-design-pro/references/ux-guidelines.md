# UX Guidelines

99 rules across the categories below.

## Categories

### Accessibility
1. Meet WCAG contrast for text, UI controls, and charts.
2. Preserve visible focus states on every interactive element.
3. Ensure keyboard path mirrors visual reading order.
4. Never rely on color alone for status.
5. Use descriptive labels over placeholder-only inputs.
6. Support zoom to 200% without breaking task completion.
7. Provide touch targets large enough for mobile workflows.
8. Expose semantic headings and landmark structure.
9. Use motion reduction fallbacks for sensitive users.
10. Make error recovery explicit and actionable.
11. Use live regions carefully for async updates.

### Interaction States
12. Define default, hover, focus, active, disabled, loading, success, and error states.
13. Do not hide primary actions during loading unless irreversible.
14. Use optimistic updates only when rollback is clear.
15. Keep skeletons shape-matched to final content.
16. Show empty states with next-step guidance.
17. Differentiate no-results from no-data and no-permission.
18. Retain row context after inline actions.
19. Use pending states for long-running actions.
20. Show save confidence with timestamp or state label.
21. Surface autosave failures immediately.
22. Make destructive actions harder than reversible ones.

### Forms
23. Group fields by mental model, not backend schema.
24. Use single-column forms by default for accuracy.
25. Place helper text before the error happens when stakes are high.
26. Validate after intent, not on first keystroke.
27. Prefer input masks only when they reduce mistakes.
28. Separate formatting hints from business rules.
29. Use inline errors near the source field.
30. Preserve user input on submit failure.
31. Allow draft save for long forms.
32. Use review steps for legal or financial submissions.
33. Mark optional fields explicitly.
34. Keep primary action sticky in long forms.

### Navigation
35. Expose location, available moves, and current scope.
36. Keep global nav stable across product areas.
37. Use breadcrumbs for deep hierarchies, not shallow apps.
38. Avoid more than 2 competing primary nav systems.
39. Persist user filters when returning to lists.
40. Make back behavior predictable in modals and side panels.
41. Use tabs only for peer views of the same object.
42. Use sidebars for area switching, not transient actions.
43. Prefer command search when entities exceed menu scale.
44. Show unsaved-changes guards before route exits.

### Feedback Patterns
45. Acknowledge every user action with visible feedback.
46. Use toast for lightweight confirmation, not important blockers.
47. Pin critical job progress in-context when users must watch it.
48. Make success messages specific about what changed.
49. Write error messages with cause + next step.
50. Differentiate system failure from validation failure.
51. Show retry affordances for network-dependent actions.
52. Log background job status in activity/history views.
53. Use confirmation dialogs only for costly mistakes.
54. Avoid celebratory effects in operational workflows.

### Layout & Density
55. Use spacing to signal hierarchy before adding borders.
56. Keep scan lines short in text-heavy panels.
57. Anchor page titles, filters, and actions consistently.
58. Use sticky headers only when context would otherwise disappear.
59. Protect table readability with row height discipline.
60. Support one-handed action zones on mobile.
61. Use cards when content chunks differ; use tables when comparison matters.
62. Avoid center-aligned forms in business workflows.
63. Use detail panels to preserve list context.
64. Keep critical metrics above the fold only if they drive action.

### Animation & Motion
65. Use motion to explain state change, not decorate screens.
66. Keep routine transitions under ~200ms.
67. Use easing that feels stable, not playful, in enterprise apps.
68. Animate between related states with shared geometry.
69. Do not animate every card on load in dense dashboards.
70. Use subtle highlight pulses for live updates.
71. Fade disabled controls only if labels remain legible.
72. Respect prefers-reduced-motion.
73. Reserve delight motion for milestones, not every save.

### Data & Tables
74. Freeze only the columns needed to preserve understanding.
75. Support resize, wrap, or truncation intentionally.
76. Make sorting and filtering state always visible.
77. Use row actions consistently at one edge.
78. Expose bulk selection with clear count and escape path.
79. Show data freshness for real-time surfaces.
80. Use inline drill-down when it reduces context loss.
81. Keep zebra striping subtle.
82. Provide CSV/export only when data semantics are stable.
83. Use sticky totals where financial accuracy matters.

### Content & Empty States
84. Name things the way operators name them.
85. Use microcopy to reduce decision friction.
86. Default empty states to action-oriented guidance.
87. Avoid lorem-style placeholders in shipped prototypes.
88. Keep buttons verb-led and specific.
89. Show system constraints before users hit them.
90. Use examples for unfamiliar input formats.
91. Write permission-related empty states without blame.
92. Tell users what they can do next, not just what is missing.
93. Avoid jargon unless the audience is expert by default.

### Theme & Modes
94. Design light and dark mode together, not sequentially.
95. Recheck elevation, border, and disabled states in both themes.
96. Preserve semantic meaning when hue shifts between modes.
97. Use theme tokens instead of direct color values.
98. Audit chart colors independently in dark mode.
99. Test screenshots, print views, and embeds if supported.

## Severity heuristic
- Break accessibility or error-recovery rules only with explicit product justification.
- In B2B SaaS, predictable interaction beats visual novelty.
- If a rule conflicts with speed, protect task completion first, then refine polish.
