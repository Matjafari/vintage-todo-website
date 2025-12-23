Vintage To‑Do List Website (No Images)

What this is
- A single-file website (index.html) with a 1930s “ledger” look using only HTML/CSS (no images).
- Daily schedule (08:00–23:00), monthly calendar previews, task details, and a “success” pie chart.
- Goals with progress bars. You can connect a task to a goal; when you mark the task done, its duration adds to the goal.

Important reality check (because physics)
- The password gate is CLIENT‑SIDE only. It blocks casual viewers, not someone who knows how to open devtools.
  If you need real protection, you must host behind real auth (server / Cloudflare Access / etc).
- Your data is stored in your browser (localStorage). It persists on the same device + browser only.
  It does NOT automatically sync across devices.

How to run locally (fastest)
1) Unzip.
2) Open index.html in your browser.

How to publish on GitHub Pages
1) Create a GitHub repo (public).
2) Upload index.html to the repo root.
3) In repo Settings -> Pages:
   - Source: Deploy from a branch
   - Branch: main / root
4) You’ll get a URL like https://<username>.github.io/<repo>/

Password
- 88106420
