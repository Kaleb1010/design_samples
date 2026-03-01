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
            9. - [ ] Token Header V3 — get user feedback, iterate on glass treatment + layout
               - [ ] - [ ] Define whether to keep horizontal stats or go more vertical (v0 reference influence)
               - [ ] - [ ] T1 intelligence cards (Wave, Narrative, Security, Peak Score) — next after header approved
              
               - [ ] ## In Progress
               - [ ] - [x] Token Header component — above-the-fold "should I care?" strip (V3 with collapsible tabs)
              
               - [ ] ## Done
               - [ ] - [x] Repo structure set up (components/, tasks/, screens/)
               - [ ] - [x] Session log created (tasks/session-log.md)
               - [ ] - [x] Build sequence agreed — Token Page first, Dashboard last
               - [ ] - [x] Aesthetic direction locked — Superhuman-inspired warm glass dark mode
               - [ ] - [x] Token Header V1 — flat/cold (rejected, used as learning)
               - [ ] - [x] Token Header V2 — glass treatment, warm palette, hover states
               - [ ] - [x] Token Header V3 — collapsible tabs (Docs/Dossier/Trade) with keyboard shortcuts
               - [ ] - [x] Design tokens V1 established (bg, glass, text hierarchy, semantic colors, wave colors)
               - [ ] - [x] Primitives created: GlassPill, Sparkline, AttentionRing, Stat, TabBtn, ActionBtn, DossierCard, TradeCard, LinkRow, Icon
               - [ ] - [x] Context save protocol established (proactive + manual)
               - [ ] - [x] Reference research doc reviewed (Linear, Superhuman, Stripe, Perplexity, Amie, Raycast)
              
               - [ ] ## Blocked
