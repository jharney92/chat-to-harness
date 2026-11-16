# From Chat to Harness

A field guide for advertising students: from chatting with AI to directing agents that build working apps and workflows.

This repository is the finished static site. There is no build step.

- `index.html` is the hub. `module-01.html` to `module-21.html` are the lessons.
- `kit.html` and `downloads/harness-starter-kit.zip` are the starter files.
- `cards.html` holds the tool cards.
- `deck-1.html` to `deck-5.html` are the teaching slides, with speaker notes.
- `videos/` holds the eight explainers with captions.

## Deploy on Vercel

1. In Vercel, choose Add New, then Project, and import this repository.
2. Leave Framework Preset as Other. Leave the build command and output directory empty.
3. Deploy. Every later push to `main` redeploys.

## Preview locally

    python3 -m http.server 8000

Then open http://localhost:8000.
