# ISO Integrated Management Systems at Porcelanosa

Single-page static site: decision brief on integrating ISO 9001 and 14001, adding ISO 27001 and piloting ISO 42001 (AI) at Porcelanosa. Includes a break-even calculator and a 6-question quiz.

No build step, no dependencies (only the Manrope font from Google Fonts).

## Edit content

All content (cards, tables, costs, quiz, sources) lives in the data arrays at the bottom of `index.html`. Change a number or a question by editing one line.

Before publishing, replace the yellow placeholders: team name, members, course, and the AI-use statement in the Sources section.

## Publish with GitHub + Render

1. Create a **public** GitHub repository (e.g. `iso-ims-porcelanosa`) and upload `index.html`, `render.yaml` and `README.md`.
2. On https://dashboard.render.com choose **New → Static Site** and connect the repository.
3. Leave **Build Command** empty and set **Publish Directory** to `.`, then **Create Static Site**.
4. After about a minute you get a public URL like `https://iso-ims-porcelanosa.onrender.com`. Open it in an incognito window to confirm it works without login.

Faster alternative: GitHub Pages (repository **Settings → Pages**, branch `main`, folder `/ (root)`).

Every commit to `main` redeploys automatically, so make all edits before the deadline.
