# Troopool

Interactive case study & high-fidelity prototype for **Troopool** — _LinkedIn × sRide · the network is the product_.

## Contents

- **`troopool-v4.html`** — the v4 interactive mobile prototype (iPhone frame, full navigable flow) with a built-in **Figma-style commenting layer**: turn on comment mode, drop pinned comments on any screen, reply in threads, and resolve — all synced in **real time** via Supabase so anyone you share the link with can review live.
- `case-study.html`, `research.html`, `business-analysis.html`, `concept.html`, `flow-audit.html`, `user-stories.html`, `presentation.html` — supporting case-study pages.
- `index.html` — entry page.
- `Troopool-Case-Study.pdf` / `.pptx` — exported case-study deck.

## The comments layer

Open `troopool-v4.html` in a browser (or host it) and share the link. Reviewers:

1. Set their name (top of the Comments panel) and pick a colour.
2. Toggle **Comment mode** (or press `C`) and tap anywhere on the prototype to drop a pin.
3. Reply within a thread, **resolve** when addressed, and see everyone's comments + live presence update in real time.

Comments are scoped per screen and stored in Supabase (`comment_threads` + `comments` tables with realtime + RLS).
