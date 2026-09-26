# Good Scan Client Audit Template

A production-grade, 1-shot GitHub Template repository for hosting executive Good'Ai client forensic audits on GitHub Pages.

---

## How to Create a New Client Audit (Zero Local Machine Required)

### Step 1: Use This Template
1. Click the green **"Use this template"** button at the top of this repository.
2. Select **"Create a new repository"**.
3. Name it `<clientname>-audit` (e.g. `acme-audit`).
4. Set visibility to **Public**.

### Step 2: Upload Client Assets
1. Open the newly created repository in your browser.
2. Navigate into the `assets/` folder.
3. Drag & drop your client files:
   - `audio.m4a` (Podcast / audio breakdown)
   - `video.mp4` (Forensic walkthrough)
   - `info.png` (Strategy roadmap infographic)
   - `deck.pdf` (Executive slide deck)
   - `data_table.csv` (Comparison data table)
   - `mindmap.json` (Forensic mindmap)
   - `dossier.zip` (One-click executive bundle under 100MB)
4. Update `index.html` with client scores and name (or let your AI assistant do the find-and-replace).

### Step 3: Automatic Publishing
GitHub Actions will automatically build and publish the live portal to:
`https://ktg-one.github.io/<clientname>-audit/`

---

## Brand System
- **Palette**: Warm Cream (`#f6f3ea`), Terracotta (`#ab4b3d`), Sage (`#d8dfca`), Ink (`#2f3a33`).
- **Typography**: Fraunces Display + Manrope UI.
- **Wordmark**: `Good'Ai` (Manrope Extra Bold + colored apostrophe).
- **Emblem**: Good'Ai Australia Headphone Mark (`assets/logo.png`).
