# Novel Map AI
Paste a web-novel URL and scan discovered chapter links for recurring character names and locations.

## Run
npm install
npm start
Open http://localhost:3000

## Deploy
Works on Node.js hosts such as Render/Railway. No API key required for this first heuristic version.

## Limits
Sites protected by Cloudflare/login/robots restrictions may block server fetching. Extraction is heuristic, not a definitive NLP/LLM story bible. Default UI requests up to 120 chapters; backend caps at 300.
