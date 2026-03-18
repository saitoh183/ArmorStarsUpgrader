# ArmorStarsUpgrader

Version: v1.1.0
Updated: 2026-03-17

Single-file Once Human armor blueprint star planner.

Supports:
- Armor-only blueprint planning
- Category-only star jumps
- Full-star conversion routing through owned armor set and owned key gear blueprints
- Matching 60 XP legendary set and exact key gear logic
- LocalStorage persistence
- JSON export and import
- Worker-based generation so the UI stays responsive

Recent improvements:
- Fragment inputs stay focused while typing
- General fragment XP totals update in place instead of rerendering the full table
- Generate runs in a Web Worker with cancel support, progress feedback, and timing
- Search uses bounded best-first exploration and returns best-so-far if limits are reached
- Piece-level ownership now controls valid conversion destinations and 60 XP matching eligibility

Run locally:
1. Open `index.html` in a modern browser.
2. Enter your current piece, owned armor set pieces, owned key gear pieces, and fragment inventory.
3. Click `Generate Path`.
