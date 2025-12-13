# Network Visualization (User Guide)

Run
- In the project folder run `python -m http.server 8000`
- Open `http://localhost:8000/network_vis.html`

How to use
- Dataset dropdown (left): switch dataset (default Stock, or BLM).
- Mode buttons (left): switch view (Attitude / News Diffusion / Emotion / Rec.Cycle).
- Timeline (bottom): drag the Round slider; the graph updates per round.
- Hover nodes: see per-round details; in Rec.Cycle, see rec count and reasons; hover speech bubbles (if any) to read post content.
- Legend (top-left): updates automatically with the current mode/data to explain colors.
