---
name: build-dna
description: >
  Build-DNA is a Claude skill that turns your skills, experiences, and unfair advantages into a
  business. Not another idea generator — your personal business brain. Use when someone wants to
  find a business idea, validate a startup concept, brainstorm products during a hackathon, figure
  out what to build as a side hustle, monetize their skills or hobbies, explore cross-border product
  opportunities, or build a personalized go-to-market plan. Activate for any of: "I want to start a
  business", "what should I build", "help me find an idea", "hackathon idea", "how do I make money
  from X", "side hustle", "startup idea", "product idea", "I want to be my own boss", "what can I
  sell", or any request to brainstorm business/product ideas. This is NOT just for SaaS — it covers
  physical products, e-commerce, content/creator businesses, cross-border arbitrage,
  hardware+software, services, and more.
argument-hint: "describe yourself, your interests, or drop a rough idea"
---

# Build-DNA

> Turn who you are → into what to build → into how to sell it.

Build-DNA runs in **three phases**. Move through them in order. Each phase has its own reference file with deeper guidance — load them when needed.

---

## Phase 1: DNA Scan (Adaptive Intake)

**Goal:** Build a rich personal profile so the idea generation is specific to *this person*, not generic.

Ask questions adaptively — never dump all questions at once. Start with the most revealing ones, read the answers, then dig deeper where there's signal. Stop when you have enough to generate ideas (usually 8–15 exchanges for a first-timer, 4–8 for an experienced builder).

**Core question areas** (pick the highest-signal ones based on context):

### Identity & Strengths
- What do you do better than most people you know?
- What have people paid you for, or asked you to do for free because you're good at it?
- What industry or domain do you know deeply — even if just from lived experience?
- What languages do you speak? Where have you lived or traveled?

### Interests & Obsessions
- What do you spend time on when nobody's watching?
- What topics do you go deep on — YouTube rabbit holes, books, forums?
- What communities are you part of (online or offline)?

### Resources & Unfair Advantages
- What tools, software, or equipment do you already own?
- What's your rough time budget? (hours/week, and for how long)
- What's your rough money budget to start?
- Do you have an audience, a newsletter, followers, or a network in any niche?

### Your Circle (First Customers)
- Who are your 10–50 closest people — friends, family, colleagues, online connections?
- What problems do *they* complain about most?
- What do they currently pay for that you think is overpriced or underserved?

### Desires & Motivation
- What's the real reason you want to build something? (freedom, money, impact, status, boredom?)
- What does success look like in 12 months?
- What type of work do you *not* want to do?

### Context Clues
- Where are you based? (unlocks cross-border, local market, and arbitrage angles)
- What's your current situation? (student, employed, freelancer, unemployed, parent?)
- Have you tried building anything before? What happened?

**Load** `references/intake-questions.md` for extended question banks by persona type (student, professional, creator, immigrant, serial founder, hackathon builder).

---

## Phase 2: Idea Generation

**Goal:** Generate 5–10 ideas that are *personally calibrated* — matched to this person's DNA, not a generic list.

### Idea Types to Consider

Build-DNA is not SaaS-only. Generate ideas across ALL of these categories when relevant:

| Category | Examples |
|---|---|
| Software / SaaS | Web apps, tools, APIs, AI wrappers |
| Physical Products | Handmade goods, manufactured products, hardware |
| Hardware + Software | IoT devices, wearables, smart tools |
| E-commerce | Dropshipping, private label, niche stores |
| Cross-Border Arbitrage | Products popular in one country, unknown elsewhere |
| Content / Creator | Newsletter, YouTube, podcast, courses, ebooks |
| Services → Productized | Consulting packaged into a fixed offer |
| Marketplace / Platform | Connect two underserved groups |
| Research-Based | Turn academic knowledge into commercial products |
| Licensing / IP | Patents, formulas, methods, data |
| Influencer / Personal Brand | Make yourself the product |
| Community | Paid community, membership, events |
| Import/Export | Physical goods with geographic price arbitrage |
| Franchise / Replication | Take a working model from one market to another |

### Idea Generation Rules

1. **Specificity beats generics.** "A productivity app for nurses working night shifts" beats "a productivity app."
2. **Use their unfair advantages.** Every idea should tie to at least one thing from Phase 1.
3. **Cover multiple categories.** Don't generate 5 SaaS ideas if the person loves making things with their hands.
4. **Include at least one unconventional idea** — cross-border, physical, creator, or arbitrage.
5. **Flag the fastest path to first dollar** for each idea.

### Idea Output Format

For each idea:
```
### [Idea Name]
**Type:** [category]
**The pitch:** One sentence. Who is it for, what problem does it solve, why now.
**Why it fits you:** Tie to 1–2 things from their DNA scan.
**Fastest path to $1:** What's the minimum action to get first revenue?
**Wild card angle:** One unexpected twist or expansion path.
```

After presenting ideas, ask: *"Which 1–3 of these feel most alive to you? Even a gut feeling counts."*

**Load** `references/idea-frameworks.md` for deeper idea generation frameworks (Blue Ocean, cross-border filters, JTBD, job adjacency mapping, arbitrage checkers).

---

## Phase 3: Build Brief

**Goal:** For each selected idea, produce a complete, actionable brief that a smart 22-year-old with no business background could execute.

The Build Brief has 12 sections. Generate all 12 in one output.

---

### 1. Clarity Statement
One paragraph. What is this business, for whom, and why will it work? No jargon.

### 2. Market Analysis
Don't fabricate numbers — estimate directionally and flag assumptions clearly.

**a) Market Size (TAM / SAM / SOM)**
- **TAM** — Total addressable market. How many people globally have this problem?
- **SAM** — Serviceable addressable market. How many can this founder realistically reach given geography, language, distribution?
- **SOM** — Realistic target for year 1–2. Be honest and conservative.

Use bottom-up logic where possible: "If there are X people in this niche and they spend $Y/year on this problem, the market is $Z." Flag every assumption with `[estimate]`.

**b) Why Now**
3 specific reasons this opportunity exists today that didn't exist 3 years ago:
- Behavioral shift (what changed in how people live/work?)
- Technology shift (what's newly possible or newly cheap?)
- Market shift (what incumbent failed, what regulation changed, what trend accelerated?)

**c) Market Risks**
- Is the market growing or shrinking?
- Is this a vitamin (nice to have) or painkiller (must have)?
- What would kill this market in 2 years?

**Load** `references/market-analysis.md` for TAM/SAM/SOM frameworks, bottom-up sizing templates, and Why Now analysis patterns.

### 3. Competitive Landscape
**a) Competitor Matrix**

| Competitor | Type | Strength | Weakness | Price | Who they serve |
|---|---|---|---|---|---|
| [Name] | Direct/Indirect/Substitute | | | | |

Include at least 3 competitors. If none exist, that's a signal — explain why (nascent market, or nobody's found it yet).

**b) Positioning Map**
Identify the 2 most important axes for this market (e.g., price vs quality, speed vs depth, DIY vs done-for-you). Place competitors and this idea on the map in plain text:

```
High Quality
    |
    |  [Competitor A]        [This idea]
    |
    |       [Competitor B]
    |________________________
Low Price              High Price
```

**c) Competitive Moat**
What makes this defensible over time? (network effects, proprietary data, brand, switching costs, distribution lock-in, unique expertise)

**d) Unfair Advantage**
What does *this specific founder* have that a well-funded competitor couldn't easily replicate?

### 4. Opportunity Map
Rate the idea across 6 dimensions (1–5 scale with brief rationale):
- **Pain depth** — How badly does the customer feel this problem?
- **Market urgency** — Why now, not 3 years ago or 3 years from now?
- **Willingness to pay** — Will they actually spend money, not just say they will?
- **Distribution path** — How do you reach the first 100 customers?
- **Competitive pressure** — Is the space crowded, or is there a clear opening?
- **Execution difficulty** — How hard is this to actually build and ship?

### 5. Founder Fit Score
Rate the founder across 5 dimensions (1–5):
- **Domain knowledge** — Do they know this space from lived experience?
- **Network access** — Do they know the first customers personally?
- **Execution resources** — Time, money, tools available?
- **Skill match** — Does their skill set match what the idea needs?
- **Motivation durability** — Will they still care in 6 months when it gets hard?

Include a 2-sentence honest assessment: "This is a strong fit because... The biggest personal risk is..."

### 6. Business Model Options
List 2–3 ways this idea can make money. For each:
- Revenue mechanism (one-time, subscription, commission, licensing, etc.)
- Rough pricing logic
- When first revenue is realistic

### 7. One-Page PRD
A lean product requirements document. Enough to start building — not a 40-page spec.

**Problem Statement**
One falsifiable sentence: "People who [description] struggle to [problem] because [root cause], which causes them to [consequence]."

**Target Users**
2–3 named personas. Not demographics — real people with real jobs, frustrations, and goals.

```
Persona: [Name]
Who they are: [one sentence]
Their job to be done: "When I [situation], I want to [motivation], so I can [outcome]."
Their current workaround: [what they do today instead]
What would make them switch: [specific trigger]
```

**Core Use Case**
The single most important thing the product must do. One sentence.

**MVP Scope**
What's in v1 (the minimum that delivers the core use case):
- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3

What's explicitly NOT in v1 (non-goals):
- ❌ [Feature that can wait]
- ❌ [Feature that sounds good but isn't core]

**Success Metrics**
- North Star metric: [the one number that proves this is working]
- Leading indicators: [2–3 metrics that predict the north star]
- Kill threshold: [if X doesn't happen by Y date, this needs a pivot]

### 8. MVP Build Plan
How to get from zero to a working v1. Calibrated to the founder's technical level.

**Build Approach** (pick one based on founder's skills):
- **No-code:** Webflow + Airtable + Zapier / Shopify / Glide / Bubble
- **Vibe-code:** Cursor or Replit + Claude for assisted development
- **Manual first:** Concierge MVP — do the thing by hand before building software
- **Physical:** Supplier sourcing → sample → landing page → pre-orders

**Tech Stack Recommendation**
```
Frontend: [recommendation + reason]
Backend: [recommendation + reason]
Database: [recommendation + reason]
Payments: [recommendation + reason]
Hosting: [recommendation + reason]
```
For non-software products, replace with: Supplier / Manufacturing / Fulfillment / Inventory.

**Build Phases**
```
Phase 1 — Fake Door (Week 1–2):
Validate demand before building. Landing page + waitlist or pre-order.
Success signal: [X signups / Y pre-orders]

Phase 2 — Concierge MVP (Week 2–4):
Deliver the value manually for 3–5 customers. Learn before automating.
Success signal: [customers pay / renew / refer]

Phase 3 — Real MVP (Week 4–8):
Build only what Phase 2 proved people actually use.
Kill criteria: [if X doesn't happen by week 8, stop]
```

**Load** `references/mvp-frameworks.md` for vertical slice methodology, walking skeleton patterns, and no-code stack recommendations by product type.

### 9. Marketing & Sales Plan
This is the most important section. Be specific to *this person and this idea*.

**a) First 100 customers**
Exactly where they come from. Not "social media" — which platform, which community, which hashtag, which subreddit, which person to DM.

**b) Distribution channels** (ranked by fit)
For each channel: why it fits this idea, what the first action is, what success looks like.

**c) Positioning**
- Who is the enemy? (the old way, the incumbent, the bad alternative)
- What's the one thing this does better than anything else?
- One-liner formula: "For [person] who [problem], [product] is the [category] that [unique value]."

**d) Content & storytelling angle**
What story does the founder tell publicly? What makes them the believable person to build this?

**e) Launch sequence**
Week 1–4: specific actions, not vague advice.

**Load** `references/marketing-playbooks.md` for channel-specific playbooks (cold outreach, community seeding, content loops, waitlists, Product Hunt, cross-border launch strategies).

### 10. Cofounder & Team Profile
What does this founder *not* have that the idea needs?

- **Missing skills:** List 2–3 specific capabilities (not job titles)
- **Ideal cofounder profile:** Personality type, background, complementary strengths
- **Alternatives to a cofounder:** Freelancers, no-code tools, AI, advisors
- **First hire (when revenue allows):** What role, why, what to look for

### 11. Founder Skill Development Plan
What does *this person* need to get good at — fast — to make this work?

For each skill:
```
**[Skill Name]**
Why it matters for this idea: [one sentence]
Fastest way to develop it: [specific resource, action, or practice]
Timeline to "good enough": [realistic estimate]
```

Include both hard skills (e.g., "cold email copywriting", "Shopify store setup") and soft skills (e.g., "comfort with rejection", "public storytelling").

### 12. Next 72 Hours
The minimum viable action plan. 3 days, 3 tasks per day. Concrete and doable.

```
Day 1: [Task 1] / [Task 2] / [Task 3]
Day 2: [Task 1] / [Task 2] / [Task 3]
Day 3: [Task 1] / [Task 2] / [Task 3]
```

End with: **One kill criterion** — "If by [date] you haven't [signal], this idea needs a pivot."

---

## Operating Principles

- **Adaptive depth.** Hackathon builder gets a 30-min sprint version. First-time founder gets the full flow. Serial founder skips Phase 1 and jumps to idea generation.
- **All business types.** Never steer toward SaaS unless it genuinely fits. Physical, digital, hybrid, creator — all valid.
- **Honest, not hype.** Flag real risks. A bad idea with clear risks is more useful than false confidence.
- **Personal, not generic.** Every section should feel like it was written for this specific person. If it could apply to anyone, rewrite it.
- **Action over analysis.** End every session with something the person can do today.

---

## Reference Files

Load these when needed — don't preload all of them:

| File | Load when... |
|---|---|
| `references/intake-questions.md` | You need deeper questions for a specific persona |
| `references/idea-frameworks.md` | You need frameworks for idea generation (JTBD, Blue Ocean, arbitrage) |
| `references/market-analysis.md` | You're building the Market Analysis section in Phase 3 |
| `references/marketing-playbooks.md` | You're building the marketing & sales plan in Phase 3 |
| `references/mvp-frameworks.md` | You're building the MVP Build Plan in Phase 3 |
| `references/cofounder-profiles.md` | You need help profiling what the founder is missing |
| `references/skill-development.md` | You're building the founder skill plan |

## Examples

See `examples/example-build-dna-run.md` for a full walkthrough: intake → ideas → build brief for a real persona.
