# Good Scan™ Client Delivery System
> **Official Good'Ai Publishing Standard for Executive Forensic Audits**  
> *Turn raw AI research into a client briefing portal hosted on GitHub Pages in under 60 seconds.*

---

## What Is A Good Scan?

A **Good Scan** is Good'Ai's flagship forensic audit deliverable for business owners and boards. 

Instead of emailing messy attachments or a dry 40-page PDF that nobody reads, a Good Scan delivers a **bespoke, responsive executive web portal** with:
- **Hero Diagnostic Score** with animated count-up counter (0–100 scale).
- **Interactive Risk Architecture Flowchart** (click-to-zoom SVG modal).
- **15-Min Audio Overview** (native HTML5 player).
- **Forensic Video Walkthrough** (native embedded video).
- **1-Click Executive Download Dossier** (ZIP, Slide Deck PDF, Mindmap, CSV Matrix).
- **Direct Workspace Link** to their interactive Personal Knowledge Bot.

👉 **[View Live Benchmark Example (BOSS Forensic Audit)](https://ktg-one.github.io/boss-audit/)**

---

## How To Create A New Client Audit (3 Steps)

Anyone on the team can create and publish a new client audit **100% in the web browser** without installing Git, Python, or command-line tools.

### Step 1: Generate the Client Repository
1. Go to the master template: **[https://github.com/ktg-one/goodscan-template](https://github.com/ktg-one/goodscan-template)**
2. Click the green **"Use this template"** button in the top right.
3. Select **"Create a new repository"**.
4. Set Repository Name to: `<clientname>-audit` *(e.g. `acme-audit`, `boss-audit`)*.
5. Set Visibility to **Public** and click **Create repository**.

### Step 2: Add Client Media
In your newly created repository:
1. Click into the **`assets/`** folder.
2. Click **Add file** ➔ **Upload files** and drag in your client deliverables:

| Standard Filename | What It Contains | Required? |
|---|---|:---:|
| **`audio.m4a`** | 15-minute forensic audio deep-dive / podcast | Yes |
| **`video.mp4`** | Screen walkthrough / teardown video | Recommended |
| **`info.png`** | High-resolution strategic remediation roadmap | Yes |
| **`deck.pdf`** | Executive board slide deck | Yes |
| **`data_table.csv`** | Competitive comparison matrix | Optional |
| **`mindmap.json`** | Mindmap node structure | Optional |
| **`dossier.zip`** | Pre-packaged download ZIP (<100MB) | Yes |
| **`logo.png`** | Good'Ai Australia headphone logo | *Pre-installed* |

3. Click **Commit changes**.

### Step 3: Update Client Scores & Text
1. Click back to root, open **`index.html`**, and click the pencil icon ✏️ (or press `.` on your keyboard to open the full web editor).
2. Find & replace:
   - Client name (e.g. replace `Business One Stop Shop` with `Acme Corp`)
   - Domain (e.g. replace `boss.asn.au` with `acme.com.au`)
   - Score numbers (e.g. update `56` to your score)
3. Click **Commit changes**.

### Done! Live URL:
Within 30 seconds, GitHub Actions automatically deploys the site live to:
👉 **`https://ktg-one.github.io/<clientname>-audit/`**

---

## Brand & Design System

Every Good Scan adheres strictly to the **Good'Ai Australia Design System**:
- **Palette**: Warm Cream Paper (`#f6f3ea`), Terracotta Accent (`#ab4b3d`), Botanical Sage (`#d8dfca`), Deep Ink Black (`#2f3a33`).
- **Typography**: Editorial **Fraunces** serif (headlines) + **Manrope** sans (UI & data).
- **Wordmark**: Native vector text `Good'Ai` (`Manrope` Bold + terracotta apostrophe).
- **Emblem**: Official Good'Ai Australia Headphone Mark (`assets/logo.png`).

---

## CLI / Automation Method (For Engineers & AI Agents)

If running from the Good'Ai operational terminal (`03` vault):

```bash
python .agents/skills/goodscan-pipeline/scripts/pipeline.py \
  --zip "C:\path\to\Client.zip" \
  --client "clientname" \
  --deploy
```

- **Skill Authority**: [`.agents/skills/goodscan-pipeline/SKILL.md`](../.agents/skills/goodscan-pipeline/SKILL.md)
- **Engine Script**: [`.agents/skills/goodscan-pipeline/scripts/pipeline.py`](../.agents/skills/goodscan-pipeline/scripts/pipeline.py)
- **Template Repo**: [https://github.com/ktg-one/goodscan-template](https://github.com/ktg-one/goodscan-template)
