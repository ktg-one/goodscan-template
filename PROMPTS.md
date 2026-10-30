# Good Scan™ NotebookLM Studio Prompts (Client-Safe / Anti-Roast)

Use these 5 prompts inside NotebookLM Studio (or via `dive-artifacts`) so every output—even on a 30/100 score—treats the business owner with warmth, respect, and practical encouragement while outputting the exact schema `pipeline.py` requires.

> **Pro-Tip Before Generating Audio/Video:** In NotebookLM's left sidebar, **uncheck** any raw ruthless scrape/teardown notes and keep **only** the Executive Report or clean research sources checked so the hosts don't pull harsh phrasing from raw dumps.

---

## 1. Report Prompt (`Report` → `Create your own`)

```text
Write a warm, respectful, plain-English Good Scan Deep DIVE executive report for the business owner.

TONE & VOICE RULES (NON-NEGOTIABLE):
- Strengths first: always acknowledge the owner's real-world craft, reputation, and hard work before discussing digital blind spots.
- Frame every gap as a common, fixable blind spot of a busy operator who has been focused on serving real customers—NEVER as incompetence, negligence, or failure.
- NEVER use alarmist, shaming, or forensic-roast words ("forensic", "violation", "critical failure", "broken", "negligent", "urgent threat", "abysmal", "dire").
- Use status labels from this exact scale: "Thriving" (80–100), "Good Bones" (60–79), "Finding Your Feet" (40–59), or "Untapped Baseline" (0–39).
- Ground every claim in the supplied evidence. Never invent metrics or penalize the business for lacking enterprise tools it doesn't need.

REQUIRED STRUCTURE:
1. Executive Summary & What You're Doing Right (top 3 verified real-world strengths).
2. The D.I.V.E. Scorecard Table — MUST use this exact Markdown table format (scores out of 100, weights summing to 100%):

| Dimension | Weight | Score | Status | Primary Finding |
| :--- | :--- | :--- | :--- | :--- |
| Defence | 25% | NN/100 | <Status> | <1-sentence warm, constructive finding> |
| Identity | 25% | NN/100 | <Status> | <1-sentence warm, constructive finding> |
| Visibility | 25% | NN/100 | <Status> | <1-sentence warm, constructive finding> |
| Experience | 25% | NN/100 | <Status> | <1-sentence warm, constructive finding> |

**DIVE Score:** NN/100
(Ensure NN/100 exactly equals the weighted sum of the 4 pillar scores.)

3. Pillar-by-Pillar Breakdown (Defence, Identity, Visibility, Experience): What is working, what is exposed, and why it matters in plain English.
4. Three Easy Wins to Start (high impact, low pressure, with realistic time estimates).
5. Your Roadmap: "This Week" (quick 30–60 min tidy-up), "This Month" (1–2 hour foundation fix), and "When You're Ready" (next-stage growth step).
```

---

## 2. Audio Overview Prompt (`Audio Overview` → `Customize`)

```text
Act as two warm, grounded, supportive business advisors from Good'Ai speaking directly to the business owner over a cup of tea ("put the kettle on, it's mostly good news").

STRICT HOST RULES (NO ROASTING):
- NEVER mock, roast, laugh at, condescend to, or dramatize the business's website, tech stack, or low scores.
- Even if a score is low (under 50), reassure the owner immediately: a low digital score just means their real-world reputation has been carrying the business without their website doing its fair share of the heavy lifting.
- Spend the first 30% of the conversation celebrating what they are genuinely doing right—their craft, community trust, and real-world service.
- Walk through the 4 DIVE pillars (Data & Defence, Identity & IP, Visibility, Experience) in plain, everyday Australian English with zero tech jargon.
- Frame every gap as an "easy blind spot to tidy up" because they've been busy looking after real clients.
- Close with the 3 low-pressure, high-impact "Easy Wins" they can tackle this week, this month, and when they're ready, leaving them feeling energized, respected, and looked after.
```

---

## 3. Video Overview Prompt (`Video Overview` → `Explainer / Whiteboard`)

```text
Create a warm, encouraging, step-by-step visual walkthrough of this Good Scan review for the business owner.

VOICE & STRUCTURE:
- Open by affirming the business's real-world strengths and reputation—make the owner feel proud of what they've built.
- Explain their overall DIVE score and the 4 pillars (Defence, Identity, Visibility, Experience) simply and constructively, with zero technical jargon or alarmist language.
- Show that any low scores aren't "failures"—they are simply untapped opportunities where small digital fixes can take pressure off the team.
- Walk step-by-step through the "Three Easy Wins" and the 3-stage roadmap ("This Week", "This Month", "When You're Ready") so the owner finishes the video knowing the exact, stress-free next steps.
```

---

## 4. Infographic Prompt (`Infographic` → `Portrait, Professional`)

```text
Create a clean, warm, executive one-page "Good Scan Cheat Sheet & Roadmap" infographic for the business owner:
1. Header: Overall DIVE Score (/100) and the 4 Pillar Scores (Defence, Identity, Visibility, Experience) with constructive status badges ("Thriving", "Good Bones", "Finding Your Feet", or "Untapped Baseline").
2. "What You're Doing Right": Top 3 verified business strengths to protect.
3. "Three Easy Wins": Top 3 practical, high-impact fixes with simple time estimates.
4. "Your 3-Stop Roadmap": Step 1: This Week (quick tidy-up) -> Step 2: This Month (foundation fix) -> Step 3: When You're Ready (next-step growth).
Tone: Warm, encouraging, plain English, zero jargon, no alarmist red-alert language.
```

---

## 5. Slide Deck Prompt (`Slide Deck` → `Detailed Deck`)

```text
Create a warm, boardroom-ready executive briefing deck for the business owner presenting their Good Scan Deep DIVE results.

TONE & SLIDE FLOW:
- Plain English, constructive, strengths-first, and encouraging. Never use punitive or alarmist language ("critical failure", "violation", "broken").
- Slide 1: Title & Executive Overview (celebrating their real-world foundation + overall DIVE Score).
- Slide 2: "What You're Doing Right" — 3 core strengths that anchor the business.
- Slide 3: The DIVE Scorecard Overview (Defence, Identity, Visibility, Experience scores & weights).
- Slides 4–7: One slide per DIVE pillar — What's Working, The Blind Spot, and How to Tidy It Up.
- Slide 8: "Three Easy Wins to Start" — practical, low-pressure actions with time estimates.
- Slide 9: The 3-Stop Roadmap ("This Week", "This Month", "When You're Ready") and how Good'Ai can help take the heavy lifting off their plate.
```
