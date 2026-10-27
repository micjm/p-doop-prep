# Prep for p(doom)

A single-page site where you set your own assumptions about catastrophic risks (AI loss of control, AI power concentration, engineered pandemics, nuclear war, grid collapse). It shows the probabilities those assumptions imply and ranks household preparedness actions to match.

You can adjust the sliders directly, or click **Take the quiz →** at the top to step through each assumption one page at a time (`#/quiz/<assumption>`) with very unlikely / unlikely / likely / very likely (10%, 30%, 70%, 90%) presets or a custom percent, the definition under each question, and expandable expert estimates. Answers are saved in `localStorage`.

Open `index.html` in a browser, or serve the folder with `python3 -m http.server`. Because routing is hash-based and state is in `localStorage`, it needs no server-side code and deploys as a static page.

This is a demo project for [Agent Duel](https://github.com/bottomless/agent-duel), blinded battles between coding agents.
