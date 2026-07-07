# Publishing this portfolio on GitHub

A 10-minute walkthrough for when you're ready to go live.

## 1. Create a GitHub account
Sign up at https://github.com/join. Pick a clean, professional username — it
becomes part of every URL (e.g. `github.com/jsmith`).

## 2. Create the repository
- **New repository** → name it e.g. `biophysics-portfolio`.
- Set **Public**. Don't add a README/licence (this folder has them).

## 3. Push this folder
```bash
git init
git add .
git commit -m "Portfolio: organised, cleaned & pruned analysis notebooks"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

## 4. Turn on GitHub Pages
- Repo → **Settings → Pages**.
- Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)** → Save.
- Live at `https://<your-username>.github.io/<your-repo>/` in ~1 min.

## 5. Wire up the links
In `index.html`, near the bottom of the `<script>`:
```js
const REPO = "your-username/your-repo";
```
This routes each notebook link through nbviewer for clean rendering. Also replace
the `[Your Name]`, email, GitHub, ORCID and LinkedIn placeholders in `index.html`
and `README.md`.

## Before you publish — checklist
- [ ] Replaced all `[Your Name]` / contact placeholders.
- [ ] No raw/unpublished data added (`.gitignore` blocks the common types).
- [ ] Decided whether `05_phd_survey_wellbeing_analysis.ipynb` should be public
      (it processes human-subjects survey data).
- [ ] Checked gene/target names in notebooks are OK to share publicly.
