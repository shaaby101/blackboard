# Blackboard

A minimalist, black-and-white virtual blackboard. Draw freehand with the
chalk pen and rough shapes automatically snap into clean lines, rectangles,
circles, and triangles. Also includes dedicated shape tools, an eraser,
undo, clear, and a fullscreen toggle.

Pure static site — one HTML file, no build step, no dependencies.

## Deploy to Vercel

**Option A — Vercel CLI**
```bash
npm install -g vercel
cd blackboard-app
vercel --prod
```

**Option B — Dashboard**
1. Push this folder to a GitHub/GitLab/Bitbucket repo.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo.
3. Framework preset: **Other** (or leave as detected — it's static).
4. Build command: none. Output directory: `.` (root).
5. Click **Deploy**.

**Option C — Drag and drop**
Go to [vercel.com/new](https://vercel.com/new) and drag the `blackboard-app`
folder onto the page.

## Local preview
```bash
npx serve .
```

## Project structure
```
blackboard-app/
├── index.html      # the entire app: markup, styles, and JS
├── vercel.json      # static-site config (clean URLs)
├── package.json      # optional, only used for local preview script
└── README.md
```
