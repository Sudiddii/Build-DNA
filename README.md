# Build-DNA

> **Turn who you are → into what to build → into how to sell it.**

A Claude skill that generates personalized business ideas and complete go-to-market plans — based on *your* unique background, skills, resources, and network. Not another SaaS idea generator. A full thinking partner that starts with you and ends with a 72-hour action plan.

---

## Why Build-DNA Exists

Most idea generators give you the same 10 ideas as everyone else.

Build-DNA is different. It starts by learning who you are — your skills, your network, your unfair advantages, where you've lived, what you obsess over, who you know. Then it generates ideas that only *you* could build. Then it tells you exactly how to sell them.

The result: business ideas matched to your DNA, not a generic market map.

---

## Who It's For

- **Vibe coders and builders** who want to ship something real, not just practice projects
- **Hackathon participants** who need a strong concept in 24 hours
- **First-time founders** who have energy but no clear direction
- **Serial entrepreneurs** who want to brainstorm new opportunities fast
- **Freelancers and consultants** who want to productize their skills
- **Anyone** who's ever said "I want to start something but I don't know what"

---

## What Makes It Different

| Feature | Build-DNA | Other idea tools |
|---|---|---|
| Starts with you, not the market | ✅ | ❌ |
| Works for physical products | ✅ | Rarely |
| Cross-border arbitrage ideas | ✅ | ❌ |
| Cofounder gap analysis | ✅ | ❌ |
| Founder skill development plan | ✅ | ❌ |
| Channel-specific marketing plan | ✅ | Generic |
| 72-hour action plan | ✅ | ❌ |
| All business types (not just SaaS) | ✅ | ❌ |

---

## What You Get

Build-DNA runs three phases:

### Phase 1 — DNA Scan
Adaptive intake: Claude asks you questions about your skills, interests, network, location, resources, and motivations. Depth adapts to your situation — a hackathon builder gets 4 questions, a first-time founder gets a full profile session.

### Phase 2 — Idea Generation
5–10 personalized business ideas across every category: software, physical products, e-commerce, content businesses, cross-border arbitrage, hardware+software, services, creator economy, and more. Each idea is tied to your specific unfair advantages.

### Phase 3 — Build Brief
For your chosen idea(s), a complete build document:

1. **Clarity Statement** — what it is, for whom, why it works
2. **Opportunity Map** — 6-dimension analysis (pain, urgency, WTP, distribution, competition, difficulty)
3. **Founder Fit Score** — honest assessment of personal fit and risks
4. **Business Model Options** — 2–3 ways to make money, with pricing logic
5. **Marketing & Sales Plan** — first 100 customers, channels, positioning, launch sequence
6. **Cofounder & Team Profile** — what you're missing, who to find, alternatives
7. **Founder Skill Development Plan** — what to learn, how fast, specific resources
8. **Next 72 Hours** — 9 concrete actions to take starting now

---

## How to Install

### Claude Code (User Level — works across all projects)

```bash
git clone https://github.com/YOUR_USERNAME/build-dna.git ~/.claude/skills/build-dna
```

### Claude Code (Project Level — shared with your team)

```bash
git clone https://github.com/YOUR_USERNAME/build-dna.git .claude/skills/build-dna
```

### Claude.ai (Projects)

1. Download this repo as a ZIP
2. In Claude.ai, open a Project
3. Upload `SKILL.md` to the project knowledge, or paste its contents into the project description

---

## How to Use

Build-DNA activates automatically when you describe what you're trying to do. Just start talking:

```
I want to start a business but I don't know what to build.
```

```
I'm at a hackathon. I need a solid idea in the next hour.
```

```
I've been a nurse for 8 years. I want to build something using what I know.
```

```
Help me find an idea I can start this weekend with $500.
```

```
I keep seeing this product in Japan that doesn't exist in Europe. How do I build a business around it?
```

Or trigger directly:

```
/build-dna I'm a 25-year-old graphic designer with 2k Instagram followers and $2k saved.
```

---

## Repo Structure

```
build-dna/
├── SKILL.md                          # Main skill entry point
├── references/
│   ├── intake-questions.md           # Extended question banks by persona type
│   ├── idea-frameworks.md            # JTBD, Blue Ocean, cross-border, arbitrage filters
│   ├── marketing-playbooks.md        # Channel-specific go-to-market playbooks
│   ├── cofounder-profiles.md         # Cofounder archetypes, fit checklist, equity ranges
│   └── skill-development.md          # Hard + soft skills by business type, timelines
├── examples/
│   └── example-build-dna-run.md       # Full walkthrough: intake → ideas → build brief
└── README.md
```

---

## Philosophy

- **Personal beats generic.** Every output should feel like it was written for you, not copy-pasted from a startup blog.
- **All business types are valid.** A Korean stationery import business is as legitimate as a SaaS. A newsletter is as real as an app.
- **Distribution deserves product-level rigor.** Where your first 100 customers come from is a product decision, not a marketing afterthought.
- **Honest over hype.** Real risks, real timelines, real kill criteria. You deserve better than false confidence.
- **Action over analysis.** Every session ends with something you can do today.

---

## Example Output

See [`examples/example-build-dna-run.md`](examples/example-build-dna-run.md) for a complete walkthrough — a 24-year-old Korean-Australian designer going from zero to a full build brief for a Korean stationery import business.

---

## Contributing

Issues and PRs welcome. Especially useful:
- Additional persona-specific question banks
- Idea frameworks for specific niches or geographies
- Example walkthroughs for different founder types
- Marketing playbooks for channels not yet covered

---

## Related Skills

Build-DNA sits alongside (does not replace):
- **`idea-os`** — turns ideas into PRDs and technical build plans; use *after* Build-DNA when you're ready to spec and build
- **marketing skills** (Corey Haines) — execution-level marketing; use *after* Build-DNA when you're running specific campaigns

---

## License

MIT — see [LICENSE](LICENSE).
