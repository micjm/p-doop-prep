# Prep for p(doom)

A single-page site where you set your own assumptions about catastrophic risks (AI loss of control, AI power concentration, engineered pandemics, nuclear war, grid collapse). It shows the probabilities those assumptions imply and ranks household preparedness actions to match.

The page opens on the sliders, exactly as before: drag each assumption, watch the implied risks and the ranked household prep update. A **Take the quiz** button at the top switches to a leaner way through the same assumptions — one question per page (`#/quiz/<assumption>`), answered very unlikely / unlikely / likely / very likely (10%, 30%, 70%, 90%), with an optional slider to fine-tune the number and the definition and other experts' figures tucked behind one-line expandables. Every assumption keeps its researched default until you answer it, and answers are saved in your browser, so the page can be closed and reopened. Routing is hash-based and state is in `localStorage`, so it needs no server-side code and deploys as a static page.

This is a demo project for [Agent Duel](https://github.com/bottomless/agent-duel), blinded battles between coding agents.
