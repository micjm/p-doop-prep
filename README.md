# Prep for p(doom)

A single-page site where you set your own assumptions about catastrophic risks (AI loss of control, AI power concentration, engineered pandemics, nuclear war, grid collapse). It shows the probabilities those assumptions imply and ranks household preparedness actions to match.

You can work through the assumptions as a quiz: one question per page (`#/quiz/<assumption>`), each answered very unlikely / unlikely / likely / very likely (10%, 30%, 70%, 90%), with an optional slider to fine-tune the exact number and the definition and other experts' figures folded away on the page. Every assumption keeps its researched default until you answer it, and answers are saved in your browser, so the page can be closed and reopened. The **Results & prep** tab (`#/results`) shows the same numbers as sliders for adjusting them directly.

Open `index.html` in a browser, or serve the folder with `python3 -m http.server`. Because routing is hash-based and state is in `localStorage`, it needs no server-side code and deploys as a static page.

This is a demo project for [Agent Duel](https://github.com/bottomless/agent-duel), blinded battles between coding agents.
