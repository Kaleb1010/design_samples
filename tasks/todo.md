# Vision UI/UX — Build Plan

## Build Sequence
1. **Token Page (Docs Mode)** — Center of gravity. Every flow ends here. Highest info density. Building it creates most reusable primitives.
2. 2. **Discover** — Scanner cards are compressed Token Pages. Filtering, bucketing, feed layout.
   3. 3. **Tokens (Portfolio/Feed)** — Personal radar. Watchlist cards + nudge accent layer designed in context.
      4. 4. **Navigation Shell + Search** — Sidebar, bottom tabs, persistent search bar. Built once we know what it frames.
         5. 5. **Dashboard** — Summary view. Built last because it pulls from everything else.
           
            6. Design tokens (colors, type, spacing) evolve naturally as we build — not a separate phase.
           
            7. ---
           
            8. ## Active
            9. - [ ] Token Page (Docs Mode) — start with above-the-fold: token header, price, wave badge, attention score, security status, sparkline
               - [ ] - [ ] Define design tokens as we go — lock colors, type, spacing during Token Page build
              
               - [ ] ## In Progress
              
               - [ ] ## Done
               - [ ] - [x] Repo structure set up (components/, tasks/, screens/)
               - [ ] - [x] Session log created (tasks/session-log.md)
               - [ ] - [x] Build sequence agreed — Token Page first, Dashboard last
              
               - [ ] ## Blocked
