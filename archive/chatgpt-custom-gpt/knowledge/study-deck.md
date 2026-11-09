# Optional: study deck and live checklist

Offer once during Phase 5. Build only if the user says yes. Both are single, self-contained HTML pages (no external scripts or stylesheets). Publish them as artifacts when the environment supports it; otherwise save as `.html` files the user can open.

Two pages, two jobs: the study deck is for the night before; the checklist is for the call itself.

## Study deck (tabbed, with write-ins)

Title: "<Company> Interview Prep: <Role>".

**Tabs:** Brief, Fit, Company, Stories, Q&A, Practice, Ask them, Glossary, After. Add a "Numbers" tab when the company publishes metrics to compare against. Later rounds get one extra tab each, named for the interviewer, added by editing, never by rebuilding.

- **Brief:** 60-second frame, five things to land, company values with a "use when" line each, Do Not Say list, write-in boxes for the opener and "why this company".
- **Fit:** requirements mapped to proof (direct, partial, gap), the three gaps with write-in boxes.
- **Company:** snapshot table, leadership, product in plain English, customers, competitors, conflicting figures.
- **Stories:** each story's beats, a write-in box per story, a red marker on any unconfirmed ending.
- **Q&A:** likely questions as tap-to-reveal flashcards with answer outlines.
- **Practice:** the scorecard, probes as flashcards, the probe table, delivery checks, a morning-of checklist with checkboxes.
- **Ask them:** questions for this round, questions to hold for later, a write-in.
- **Glossary:** collapsible groups, each term a tap-to-reveal card.
- **After:** the four reflection prompts with write-ins, a capture box, a self-score box.

Features: cross-tab search with highlight; flashcards; write-in boxes and checkboxes saved in browser storage (wrapped in try/catch, since storage can be unavailable); a "copy my notes" button; a reset button; tab routing by URL hash; light and dark mode; large type, phone and laptop readable.

All content comes from the Candidate Profile and the Phase 5 outputs. No new facts.

## Live checklist (one page, no tabs)

Title: "<Company> Interview Checklist". One page because during a call the user is either glancing or searching, and tabs serve neither.

In order:
1. Header: role, company, interviewer.
2. Delivery strip, always visible: "Answer first. One story. 90 seconds. One number. Stop on the result."
3. SAY: 5 points, always visible.
4. MY NUMBERS: each figure with its employer and time window, always visible.
5. AVOID: naming rules, number-swap risks, unconfirmed claims.
6. GAPS: 3 honest one-liners.
7. ASK: 3 questions.
8. GLOSSARY: collapsible groups, collapsed by default.

A sticky search box filters every item instantly. High contrast, big type. Built like a pilot's checklist, not a study guide.
