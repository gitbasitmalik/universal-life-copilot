# 🛠️ Universal Life Copilot — 100 Skills for Gemini

![Skills](https://img.shields.io/badge/skills-100-blue) ![Packs](https://img.shields.io/badge/packs-12-purple) ![License](https://img.shields.io/badge/license-MIT-green)

**100 plug-and-play skills that turn Gemini into a specialist for whatever you're doing today** — studying for an exam, debugging code, negotiating a raise, planning a trip, sorting a budget, or just getting through a chaotic Monday.

Every skill is a single `SKILL.md` file. Upload it once and it wakes up automatically when your request matches. No setup, no coding, no prompt engineering.

---

## 🗂️ Pick Your Pack

Skills are grouped by **who they're for**. Open a pack to see every skill with an example prompt.

| Pack | Who it's for | Skills |
|---|---|:---:|
| 🎓 [Students](agents/skills/students/) | Exams, essays, flashcards, languages, maths | 10 |
| 💻 [Developers](agents/skills/developers/) | Debugging, code review, SQL, regex, docs, system design | 10 |
| 💼 [Professionals](agents/skills/professionals/) | Resumes, interviews, salary talks, reviews, meetings | 10 |
| 🚀 [Entrepreneurs](agents/skills/entrepreneurs/) | Business plans, copywriting, pitches, customer replies | 8 |
| 🎬 [Creators](agents/skills/creators/) | Content calendars, scripts, newsletters, blogs, fiction | 6 |
| ✍️ [Writers](agents/skills/writers/) | Tone, proofreading, tricky replies, speeches, summaries | 7 |
| ⚡ [Everyday Life](agents/skills/everyday-life/) | Focus, habits, goals, decisions, inbox, weekly reviews | 9 |
| 👨‍👩‍👧 [Parents & Families](agents/skills/parents-and-families/) | Meals, cleaning, kids, pets, moving, DIY, parties | 10 |
| ✈️ [Travelers](agents/skills/travelers/) | Itineraries, packing, budgets, phrases, day trips | 5 |
| 🌿 [Health & Wellness](agents/skills/health-and-wellness/) | Meal plans, workouts, sleep, stress, journaling | 10 |
| 💰 [Personal Finance](agents/skills/personal-finance/) | Budgets, debt payoff, savings, bills, subscriptions | 9 |
| 🖥️ [Tech Beginners](agents/skills/tech-beginners/) | Tech support, security, scams, spreadsheets, prompts | 6 |

> **Not sure where to start?** Install [`life-copilot`](agents/skills/everyday-life/life-copilot/SKILL.md) — the all-rounder that tidies messy notes, plans your day, drafts emails and breaks down decisions.

---

## 📦 How to Install

### Step 1: Download the files
1. Click the green **Code** button at the top of this page.
2. Select **Download ZIP**.
3. Unzip it on your computer.

### Step 2: Upload a skill to Gemini
1. Open Gemini and click **Customise** in the left sidebar.
2. Select the **Skills** tab.
3. Click **Create** → **Upload skill**.
4. Open `agents/skills/`, pick a pack (for example `students/`), and drag **one skill folder** (for example `study-buddy/`) into the upload box.

Repeat for every skill you want. Install only the ones you'll use — fewer skills means sharper matching.

---

## 🎯 How It Works

Each skill has a description that tells Gemini **when** to activate it, and instructions that tell it **how** to respond — the structure, the techniques to use, the questions to ask, and the mistakes to avoid. Just chat normally:

| You type… | Skill that kicks in |
|---|---|
| "My exam is in 12 days and I haven't started" | 🎓 `exam-cram-planner` |
| "Getting `TypeError: cannot read properties of undefined` — here's my code" | 💻 `bug-detective` |
| "They offered me £48k, I was hoping for £55k. How do I respond?" | 💼 `salary-negotiator` |
| "Turn this YouTube video transcript into a week of posts" | 🎬 `content-repurposer` |
| "I have chicken, rice, spinach and half an onion" | 👨‍👩‍👧 `pantry-chef` |
| "Is this text from my 'bank' a scam?" | 🖥️ `scam-spotter` |
| "I owe on 3 credit cards — which do I pay first?" | 💰 `debt-payoff-planner` |
| "I keep putting off my tax return" | ⚡ `procrastination-breaker` |

---

## 📚 Full Skill Catalog

<details>
<summary><b>🎓 Students (10)</b></summary>

| Skill | What it does |
|---|---|
| [study-buddy](agents/skills/students/study-buddy/SKILL.md) | Turns notes and chapters into summaries, key concepts and a study plan |
| [flashcard-forge](agents/skills/students/flashcard-forge/SKILL.md) | Makes Anki/Quizlet-ready flashcards with a spaced-repetition schedule |
| [socratic-tutor](agents/skills/students/socratic-tutor/SKILL.md) | Teaches through guiding questions so you actually understand |
| [essay-coach](agents/skills/students/essay-coach/SKILL.md) | Sharpens thesis, structure and arguments, with draft feedback |
| [exam-cram-planner](agents/skills/students/exam-cram-planner/SKILL.md) | Builds a revision timetable backwards from your exam dates |
| [language-partner](agents/skills/students/language-partner/SKILL.md) | Conversation practice at your level, with gentle corrections |
| [math-step-solver](agents/skills/students/math-step-solver/SKILL.md) | Solves maths problems step by step, then gives you one to try |
| [citation-helper](agents/skills/students/citation-helper/SKILL.md) | Formats APA, MLA, Harvard and Chicago references correctly |
| [book-digest](agents/skills/students/book-digest/SKILL.md) | Key ideas, takeaways and discussion questions for any book |
| [skill-roadmap](agents/skills/students/skill-roadmap/SKILL.md) | A staged learning plan for any new skill |

</details>

<details>
<summary><b>💻 Developers (10)</b></summary>

| Skill | What it does |
|---|---|
| [code-explainer](agents/skills/developers/code-explainer/SKILL.md) | Explains unfamiliar code from high-level overview to line by line |
| [bug-detective](agents/skills/developers/bug-detective/SKILL.md) | Ranked hypotheses, repro steps and fixes from errors and stack traces |
| [code-review-buddy](agents/skills/developers/code-review-buddy/SKILL.md) | Severity-tagged review for bugs, security, performance and readability |
| [commit-message-writer](agents/skills/developers/commit-message-writer/SKILL.md) | Conventional Commits messages and PR descriptions from a diff |
| [readme-generator](agents/skills/developers/readme-generator/SKILL.md) | Complete, scannable READMEs for your projects |
| [sql-helper](agents/skills/developers/sql-helper/SKILL.md) | Writes, optimises and explains SQL for your dialect |
| [regex-builder](agents/skills/developers/regex-builder/SKILL.md) | Regular expressions with explanations and test cases |
| [api-docs-writer](agents/skills/developers/api-docs-writer/SKILL.md) | Endpoint docs with examples, error codes and OpenAPI snippets |
| [system-design-coach](agents/skills/developers/system-design-coach/SKILL.md) | System design walkthroughs and interview practice |
| [test-case-generator](agents/skills/developers/test-case-generator/SKILL.md) | Unit and integration tests plus edge cases in your framework |

</details>

<details>
<summary><b>💼 Professionals (10)</b></summary>

| Skill | What it does |
|---|---|
| [career-catalyst](agents/skills/professionals/career-catalyst/SKILL.md) | Resume bullets, cover letters, LinkedIn polish and mock interviews |
| [star-story-bank](agents/skills/professionals/star-story-bank/SKILL.md) | A reusable bank of STAR interview stories from your experience |
| [salary-negotiator](agents/skills/professionals/salary-negotiator/SKILL.md) | Negotiation range, word-for-word scripts and pushback responses |
| [personal-brand-builder](agents/skills/professionals/personal-brand-builder/SKILL.md) | LinkedIn posts, bios and a 2-week posting plan |
| [career-switch-navigator](agents/skills/professionals/career-switch-navigator/SKILL.md) | Transferable skills, gaps and a route into a new field |
| [performance-review-writer](agents/skills/professionals/performance-review-writer/SKILL.md) | Evidence-based self, peer and manager reviews |
| [workplace-diplomat](agents/skills/professionals/workplace-diplomat/SKILL.md) | Scripts for conflict, saying no and giving feedback |
| [first-90-days](agents/skills/professionals/first-90-days/SKILL.md) | A 30-60-90 day plan for a new role |
| [job-offer-evaluator](agents/skills/professionals/job-offer-evaluator/SKILL.md) | Side-by-side offer comparison and questions to ask |
| [meeting-minutes](agents/skills/professionals/meeting-minutes/SKILL.md) | Decisions, action items and a follow-up email from raw notes |

</details>

<details>
<summary><b>🚀 Entrepreneurs (8)</b></summary>

| Skill | What it does |
|---|---|
| [business-plan-builder](agents/skills/entrepreneurs/business-plan-builder/SKILL.md) | A lean business plan or Lean Canvas |
| [startup-idea-validator](agents/skills/entrepreneurs/startup-idea-validator/SKILL.md) | Riskiest assumptions and cheap experiments to test them |
| [marketing-copywriter](agents/skills/entrepreneurs/marketing-copywriter/SKILL.md) | Ads, landing pages and emails using AIDA and PAS |
| [product-description-writer](agents/skills/entrepreneurs/product-description-writer/SKILL.md) | Benefit-led, SEO-friendly product descriptions |
| [customer-reply-pro](agents/skills/entrepreneurs/customer-reply-pro/SKILL.md) | Calm, solution-first support replies and review responses |
| [pitch-deck-outliner](agents/skills/entrepreneurs/pitch-deck-outliner/SKILL.md) | Slide-by-slide pitch deck with speaker notes |
| [brand-name-generator](agents/skills/entrepreneurs/brand-name-generator/SKILL.md) | Brand names with rationale, taglines and checks to run |
| [freelance-proposal-pro](agents/skills/entrepreneurs/freelance-proposal-pro/SKILL.md) | Tailored freelance proposals with scope and pricing options |

</details>

<details>
<summary><b>🎬 Creators (6)</b></summary>

| Skill | What it does |
|---|---|
| [social-media-planner](agents/skills/creators/social-media-planner/SKILL.md) | Content pillars, post ideas and a posting calendar |
| [youtube-script-writer](agents/skills/creators/youtube-script-writer/SKILL.md) | Hook-first video scripts with titles and thumbnail text |
| [newsletter-writer](agents/skills/creators/newsletter-writer/SKILL.md) | Newsletters with subject lines, sections and one clear CTA |
| [blog-post-builder](agents/skills/creators/blog-post-builder/SKILL.md) | Outlined, scannable blog posts with SEO title and meta |
| [story-spark](agents/skills/creators/story-spark/SKILL.md) | Premises, characters, plot outlines and draft feedback |
| [content-repurposer](agents/skills/creators/content-repurposer/SKILL.md) | Turns one piece of content into posts, threads and shorts |

</details>

<details>
<summary><b>✍️ Writers (7)</b></summary>

| Skill | What it does |
|---|---|
| [tone-tuner](agents/skills/writers/tone-tuner/SKILL.md) | Rewrites text in any tone, with variants |
| [grammar-guardian](agents/skills/writers/grammar-guardian/SKILL.md) | Proofreads and explains the key fixes |
| [reply-wizard](agents/skills/writers/reply-wizard/SKILL.md) | Three reply options for awkward texts and DMs |
| [summary-surgeon](agents/skills/writers/summary-surgeon/SKILL.md) | TL;DR and key points from long reads |
| [plain-english](agents/skills/writers/plain-english/SKILL.md) | Turns jargon into plain language |
| [speech-writer](agents/skills/writers/speech-writer/SKILL.md) | Toasts and speeches timed for your audience |
| [card-message-writer](agents/skills/writers/card-message-writer/SKILL.md) | Heartfelt messages for any card |

</details>

<details>
<summary><b>⚡ Everyday Life (9)</b></summary>

| Skill | What it does |
|---|---|
| [life-copilot](agents/skills/everyday-life/life-copilot/SKILL.md) | The all-rounder: tidy notes, plan days, draft emails, make decisions |
| [focus-sprint](agents/skills/everyday-life/focus-sprint/SKILL.md) | Deep-work sessions with sprints, breaks and a distraction plan |
| [inbox-zero](agents/skills/everyday-life/inbox-zero/SKILL.md) | Triages messages and drafts quick replies |
| [weekly-review](agents/skills/everyday-life/weekly-review/SKILL.md) | Wins, lessons and next week's top 3 priorities |
| [goal-architect](agents/skills/everyday-life/goal-architect/SKILL.md) | SMART goals or OKRs with milestones |
| [habit-builder](agents/skills/everyday-life/habit-builder/SKILL.md) | Habits that stick, with a plan for missed days |
| [procrastination-breaker](agents/skills/everyday-life/procrastination-breaker/SKILL.md) | Finds why you're stuck and gets you started in 5 minutes |
| [decision-compass](agents/skills/everyday-life/decision-compass/SKILL.md) | Weighted decision matrix for tough choices |
| [second-brain](agents/skills/everyday-life/second-brain/SKILL.md) | Organises notes and ideas with the PARA method |

</details>

<details>
<summary><b>👨‍👩‍👧 Parents & Families (10)</b></summary>

| Skill | What it does |
|---|---|
| [grocery-list-genius](agents/skills/parents-and-families/grocery-list-genius/SKILL.md) | Aisle-sorted grocery lists from your meal ideas |
| [pantry-chef](agents/skills/parents-and-families/pantry-chef/SKILL.md) | Recipes from what's already in your kitchen |
| [cleaning-schedule](agents/skills/parents-and-families/cleaning-schedule/SKILL.md) | A realistic cleaning rota for the whole household |
| [declutter-coach](agents/skills/parents-and-families/declutter-coach/SKILL.md) | Room-by-room decluttering plan |
| [moving-checklist](agents/skills/parents-and-families/moving-checklist/SKILL.md) | Week-by-week moving plan |
| [kids-activity-ideas](agents/skills/parents-and-families/kids-activity-ideas/SKILL.md) | Age-appropriate activities for any day |
| [calm-parent](agents/skills/parents-and-families/calm-parent/SKILL.md) | Calm scripts for tantrums, bedtime and screen time |
| [pet-care-planner](agents/skills/parents-and-families/pet-care-planner/SKILL.md) | Feeding, exercise, grooming and vet routines |
| [diy-fix-it](agents/skills/parents-and-families/diy-fix-it/SKILL.md) | Safe step-by-step fixes for common home problems |
| [party-planner](agents/skills/parents-and-families/party-planner/SKILL.md) | Themes, food quantities, timeline and budget |

</details>

<details>
<summary><b>✈️ Travelers (5)</b></summary>

| Skill | What it does |
|---|---|
| [trip-planner](agents/skills/travelers/trip-planner/SKILL.md) | Day-by-day itineraries at your pace |
| [packing-pro](agents/skills/travelers/packing-pro/SKILL.md) | Packing lists for your destination and activities |
| [travel-budgeter](agents/skills/travelers/travel-budgeter/SKILL.md) | Trip cost estimates and a daily spending limit |
| [phrasebook-buddy](agents/skills/travelers/phrasebook-buddy/SKILL.md) | Key phrases, pronunciation and etiquette |
| [local-explorer](agents/skills/travelers/local-explorer/SKILL.md) | Weekend and day-trip ideas near you |

</details>

<details>
<summary><b>🌿 Health & Wellness (10)</b></summary>

| Skill | What it does |
|---|---|
| [meal-planner](agents/skills/health-and-wellness/meal-planner/SKILL.md) | Weekly meal plans with prep schedule and grocery list |
| [workout-builder](agents/skills/health-and-wellness/workout-builder/SKILL.md) | Workout plans for your goal, level and equipment |
| [sleep-reset](agents/skills/health-and-wellness/sleep-reset/SKILL.md) | Wind-down routine and a 2-week sleep diary |
| [stress-unwind](agents/skills/health-and-wellness/stress-unwind/SKILL.md) | Breathing, grounding and a calm-down plan |
| [mood-journal](agents/skills/health-and-wellness/mood-journal/SKILL.md) | Journaling prompts and gentle thought reframing |
| [healthy-swaps](agents/skills/health-and-wellness/healthy-swaps/SKILL.md) | Healthier versions of the food you love |
| [doctor-visit-prep](agents/skills/health-and-wellness/doctor-visit-prep/SKILL.md) | Symptom timeline and questions for your appointment |
| [meditation-guide](agents/skills/health-and-wellness/meditation-guide/SKILL.md) | Guided meditation scripts of any length |
| [couch-to-5k](agents/skills/health-and-wellness/couch-to-5k/SKILL.md) | A progressive run/walk plan to 5K |
| [digital-detox](agents/skills/health-and-wellness/digital-detox/SKILL.md) | Healthier screen habits and a 7-day reset |

</details>

<details>
<summary><b>💰 Personal Finance (9)</b></summary>

| Skill | What it does |
|---|---|
| [budget-builder](agents/skills/personal-finance/budget-builder/SKILL.md) | Monthly budget using 50/30/20 or zero-based budgeting |
| [expense-sorter](agents/skills/personal-finance/expense-sorter/SKILL.md) | Categorises transactions and spots spending leaks |
| [debt-payoff-planner](agents/skills/personal-finance/debt-payoff-planner/SKILL.md) | Avalanche vs snowball payoff plan |
| [savings-goal-planner](agents/skills/personal-finance/savings-goal-planner/SKILL.md) | Monthly savings target and timeline for any goal |
| [subscription-auditor](agents/skills/personal-finance/subscription-auditor/SKILL.md) | Keep, pause or cancel every subscription |
| [bill-negotiator](agents/skills/personal-finance/bill-negotiator/SKILL.md) | Call scripts to lower your bills |
| [smart-shopper](agents/skills/personal-finance/smart-shopper/SKILL.md) | Cost-per-use and comparison before you buy |
| [tax-doc-organizer](agents/skills/personal-finance/tax-doc-organizer/SKILL.md) | Tax document checklist and folder system |
| [money-basics-tutor](agents/skills/personal-finance/money-basics-tutor/SKILL.md) | Money concepts explained in plain language |

</details>

<details>
<summary><b>🖥️ Tech Beginners (6)</b></summary>

| Skill | What it does |
|---|---|
| [tech-support-buddy](agents/skills/tech-beginners/tech-support-buddy/SKILL.md) | Jargon-free fixes for everyday tech problems |
| [security-checkup](agents/skills/tech-beginners/security-checkup/SKILL.md) | A prioritised personal security checklist |
| [scam-spotter](agents/skills/tech-beginners/scam-spotter/SKILL.md) | Red flags and a verdict on suspicious messages |
| [spreadsheet-wizard](agents/skills/tech-beginners/spreadsheet-wizard/SKILL.md) | Excel and Google Sheets formulas explained |
| [prompt-polisher](agents/skills/tech-beginners/prompt-polisher/SKILL.md) | Better prompts for any AI tool, before and after |
| [digital-declutter](agents/skills/tech-beginners/digital-declutter/SKILL.md) | Tidy files, photos and cloud storage |

</details>

---

## 🧱 Repository Structure

```
agents/skills/
├── students/
│   ├── README.md
│   ├── study-buddy/
│   │   └── SKILL.md
│   └── ...
├── developers/
├── professionals/
├── entrepreneurs/
├── creators/
├── writers/
├── everyday-life/
├── parents-and-families/
├── travelers/
├── health-and-wellness/
├── personal-finance/
└── tech-beginners/
```

Every skill follows the same shape: **Instructions → Trigger Conditions → Core Directives → Clarifying Questions → Output Format → Strict Restrictions**.

---

## ⚠️ Good to Know

- Health, money, legal and DIY skills give **general information, not professional advice**. They are built to flag when you should see a doctor, financial adviser, lawyer or licensed tradesperson.
- Skills never ask for passwords, card numbers or account details. Don't paste them in.
- Always double-check important facts, prices, dates and citations.

---

## 🤝 Contributing

Got an idea for skill #101? See [CONTRIBUTING.md](CONTRIBUTING.md) for the template and guidelines. Pull requests are welcome.

## 📄 License

[MIT](LICENSE) — free to use, modify and share.
