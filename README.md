# Claude 5.5 Model Explorer

Interactive single-file comparison of **Claude Haiku 5.5, Sonnet 5.5 and Opus 5.5**: pricing, benchmarks, speed, effort levels (medium/high), cost calculator, speed race and a "which model for which task" picker.

## Run

Open `index.html` in a browser. No build, no dependencies.

## Deploy to GitHub Pages

Repo → Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.

## Update data

Edit the `MODELS` and `TASKS` objects at the top of the `<script>` in `index.html`.

- Prices, context, effort defaults: Anthropic API model table.
- Benchmarks and speed: third-party sources (linked in the page footer), approximate.
- Values marked `est` in the UI (thinking-token share per effort, Haiku cache price) are assumptions, not published numbers.
