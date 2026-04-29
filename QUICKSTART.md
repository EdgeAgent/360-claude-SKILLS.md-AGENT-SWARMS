# Claude Skills 360 — Getting Started in 10 Minutes

Master 10 high-impact skills across different domains in your first week.

---

## Verify Your Installation

Before diving in, confirm everything installed correctly. Run these commands in your terminal:

```bash
# Check skills installed
ls ~/.claude/skills/ | wc -l
# Should output: 74

# Check agents installed
ls ~/.claude/agents/ | wc -l
# Should output: 28

# Check swarms installed
ls ~/.claude/swarms/ | wc -l
# Should output: 7
```

Then open Claude Code and load a skill:

```
/skills claude-code-power-user
```

**Expected output**: The skill content loads immediately — you'll see a structured guide with sections, templates, and commands.

If skills aren't loading, restart Claude Code completely (quit → reopen). See INSTALL.md for troubleshooting.

---

## Pick Your First 10 Skills

Choose 10 high-impact skills across different domains. Each skill includes a "Quick Win" section you can complete in under 1 hour.

---

## Domain 1: Business & Entrepreneurship

### Skill 1: SaaS Idea to MVP

**What it does**: Validate a startup idea and ship an MVP in weeks without wasting time on unvalidated assumptions.

**Load it**:
```
/skills saas-idea-to-mvp
```

**Key sections**:
- Idea validation (talk to 10 customers before building)
- Tech spec creation (what to build)
- MVP scoping (ship early and often)
- Stripe integration (get paid)
- Launch checklist

**Quick win** (1 hour):
1. Write your 1-sentence idea
2. List 10 potential customers
3. Run the validation checklist
4. Score your idea (>80 = proceed)

**Next step**: Create a detailed tech spec for your MVP.

---

### Skill 2: Freelancer Proposal Engine

**What it does**: Win more contracts with persuasive proposals, SOWs, and pricing models that work.

**Load it**:
```
/skills freelancer-proposal-engine
```

**Key sections**:
- Psychology of persuasion (why clients say yes)
- Discovery questions (find real pain points)
- Proposal anatomy (structure that wins)
- Scope of Work templates
- Pricing models (hourly, fixed, value-based)

**Quick win** (30 min):
1. Pick your target service
2. Copy the proposal template
3. Fill in your unique angle
4. Customize pricing
5. Send to a warm lead

**Next step**: Create 3 customized proposals this week.

---

### Skill 3: Digital Product Launcher

**What it does**: Create and sell digital products (ebooks, courses, templates) that generate passive income.

**Load it**:
```
/skills digital-product-launcher
```

**Key sections**:
- Product idea validation (what actually sells)
- Creation workflow (tools and process)
- Platform setup (Gumroad, LemonSqueezy, Teachable)
- Sales page writing
- Launch checklist (day 1, week 1, month 1)

**Quick win** (2 hours):
1. Decide: ebook, course, template, or bundle?
2. Research 5 competing products
3. Create your unique positioning
4. Sketch your sales page outline

**Next step**: Create your first product MVP within 1 week.

---

## Domain 2: Developer Skills

### Skill 4: Claude Code Power User

**What it does**: Master advanced Claude Code techniques to work faster, smarter, and cheaper.

**Load it**:
```
/skills claude-code-power-user
```

**Key sections**:
- Hook system (run tasks on file save)
- Profile switcher (swap MCPs on demand)
- Slash command shortcuts
- CLAUDE.md architecture (project context files)
- Cost optimization (save 30-50% on API costs)
- Context management (avoid token limits)

**Quick win** (30 min):
1. Set up 1 hook (auto-format on save)
2. Create your first CLAUDE.md file
3. Test `/` shortcuts
4. Check your API token usage

**Next step**: Build a full project CLAUDE.md with structured context.

---

### Skill 5: Prompt to Production

**What it does**: Ship features from natural language description to tested, deployed code without getting stuck.

**Load it**:
```
/skills prompt-to-production
```

**Key sections**:
- Requirements clarity (avoid rework)
- Implementation sprint (with Claude Code)
- Testing strategy (unit, integration, e2e)
- Deployment checklist
- Monitoring and rollback

**Quick win** (1 hour):
1. Pick a small feature (30-min implementation)
2. Write crystal-clear requirements
3. Let Claude build it
4. Run the test checklist
5. Deploy to production

**Next step**: Use this pipeline for all future features.

---

### Skill 6: AI Pair Programmer

**What it does**: Complete workflow for building software projects with AI assistance from start to finish.

**Load it**:
```
/skills ai-pair-programmer
```

**Key sections**:
- Planning (PRD, tech spec, architecture)
- Implementation (sprint structure, daily feedback)
- Testing (automated + manual)
- Code review (quality gates)
- Handoff (documentation, deployment)

**Quick win** (3 hours):
1. Write your PRD (problem, solution, success metrics)
2. Let Claude generate tech spec
3. Build 1 feature using sprint workflow
4. Review and ship
5. Deploy with monitoring

**Next step**: Use this for your next complete feature or project.

---

## Domain 3: Marketing & Growth

### Skill 7: SEO Content Strategy

**What it does**: Build organic traffic from keyword research through content clusters and technical optimization.

**Load it**:
```
/skills seo-content-strategy
```

**Key sections**:
- Keyword research (finding intent and volume)
- Content cluster strategy (pillar + cluster articles)
- Content calendar (planning and prioritization)
- Technical SEO (crawlability, speed, structure)
- AI search optimization (ranking in AI overviews)

**Quick win** (1-2 days):
1. Pick a target niche
2. Research 20+ keywords
3. Create content cluster map (1 pillar + 5 clusters)
4. Outline first 3 articles
5. Plan publishing schedule

**Next step**: Publish your first pillar article.

---

### Skill 8: Email Marketing Playbook

**What it does**: Build an email list, write sequences, and generate revenue from your audience.

**Load it**:
```
/skills email-marketing-playbook
```

**Key sections**:
- List building strategies (landing pages, lead magnets)
- Welcome sequence (first impression)
- Nurture drip campaigns (build trust)
- Broadcast best practices (sell without spamming)
- Segmentation (personalized messaging)
- Cold outreach (B2B prospecting)

**Quick win** (2-3 hours):
1. Create landing page for lead magnet
2. Write welcome sequence (3 emails)
3. Set up email provider (Mailchimp, ConvertKit, etc.)
4. Plan first broadcast

**Next step**: Launch your landing page and collect first 100 subscribers.

---

## Domain 4: Productivity & Personal Development

### Skill 9: Resume Optimizer

**What it does**: Rewrite your resume for ATS systems, add STAR stories, and win more interviews.

**Load it**:
```
/skills resume-optimizer
```

**Key sections**:
- ATS optimization (formatting, keywords)
- STAR framework (quantify your impact)
- Keyword matching (mirror job descriptions)
- Cover letter strategy
- Interview prep (from your resume)

**Quick win** (45 min):
1. Pick a target job
2. Extract top 10 keywords from job description
3. Rewrite 3 bullet points using STAR
4. Add metrics to each bullet
5. Run through ATS checker

**Next step**: Customize for 5 target jobs.

---

### Skill 10: Autonomous Task Runner

**What it does**: Build self-correcting agents that automate repetitive work without supervision.

**Load it**:
```
/skills autonomous-task-runner
```

**Key sections**:
- Task selection (what to automate)
- Agent design (goals, tools, constraints)
- Error recovery (retry logic, fallbacks)
- Monitoring (know when agents fail)
- Cost management (prevent token waste)
- Guardrails (safety constraints)

**Quick win** (2-3 hours):
1. Pick 1 repetitive task (data entry, report generation, email classification)
2. Design the agent using the template
3. Implement basic guardrails
4. Test on 5 examples
5. Deploy

**Next step**: Build agents for 2-3 more tasks this month.

---

## Quick Reference: All 10 Skills

| # | Skill | Domain | Load Command | Time to Value |
|---|-------|--------|--------------|----------------|
| 1 | SaaS Idea to MVP | Business | `/skills saas-idea-to-mvp` | 1 hour |
| 2 | Freelancer Proposal Engine | Business | `/skills freelancer-proposal-engine` | 30 min |
| 3 | Digital Product Launcher | Business | `/skills digital-product-launcher` | 2 hours |
| 4 | Claude Code Power User | Developer | `/skills claude-code-power-user` | 30 min |
| 5 | Prompt to Production | Developer | `/skills prompt-to-production` | 1 hour |
| 6 | AI Pair Programmer | Developer | `/skills ai-pair-programmer` | 3 hours |
| 7 | SEO Content Strategy | Marketing | `/skills seo-content-strategy` | 1-2 days |
| 8 | Email Marketing Playbook | Marketing | `/skills email-marketing-playbook` | 2-3 hours |
| 9 | Resume Optimizer | Growth | `/skills resume-optimizer` | 45 min |
| 10 | Autonomous Task Runner | Automation | `/skills autonomous-task-runner` | 2-3 hours |

---

## Your First Week: Suggested Timeline

### Day 1: Setup & Exploration (1 hour)
- [ ] Complete installation (run verify commands above)
- [ ] Skim all 10 skill descriptions
- [ ] Pick your top 3 based on immediate needs
- [ ] Load one skill and read the introduction

### Day 2-3: Pick a Domain (4-6 hours)
- [ ] Choose one domain (business OR developer)
- [ ] Load all 3 skills in that domain
- [ ] Complete "Quick Win" for each
- [ ] Save 2 templates for future use

### Day 4-5: First Real Project (6-8 hours)
- [ ] Apply one skill to a real problem you have
- [ ] Follow the workflow from start to finish
- [ ] Save your work
- [ ] Document what worked and what confused you

### Day 6-7: Review & Next Steps (2-3 hours)
- [ ] Try 1 skill from a different domain
- [ ] Update CHEATSHEET.md bookmark
- [ ] Plan which skills to master next month
- [ ] Share results with a colleague or friend

---

## How to Maximize Value

### 1. Use Templates, Don't Memorize
Every skill includes templates and checklists. Copy them. Adapt them. Repeat with variations.

### 2. Combine Skills for 2x Impact
- Freelancer Proposal + Digital Product Launcher = sell your services as a product
- SaaS Idea to MVP + Revenue Dashboard = build and measure startups
- SEO Content + Email Marketing = generate leads at scale

### 3. Save Your Customizations
When you adapt a template:
1. Save your version locally
2. Use as baseline for next project
3. Refine based on results
4. Share with your team

### 4. Iterate, Don't Perfectionism
- First draft doesn't need to be perfect
- Use the skill to get 80% there
- Refine based on feedback
- Move to next skill

### 5. Join the Community
Share which skills are most valuable for you and what you're building.

---

## When You're Ready for More

Once you've mastered these 10, you have 55 more skills to explore:

See **CHEATSHEET.md** for all 65 skills organized by category.

Then explore **AGENT-GUIDE.md** for orchestrating multiple skills into autonomous agents.

---

## Success Metrics

Track your progress:

- [ ] Verified installation (74 skills, 28 agents, 7 swarms)
- [ ] Loaded 3 skills successfully
- [ ] Completed "Quick Win" for 2 skills
- [ ] Applied 1 skill to real work
- [ ] Saved 1 template for reuse
- [ ] Read CHEATSHEET.md completely

Once all checked, you're a Claude Skills 360 practitioner.

---

## Troubleshooting

**Skills not loading?**
1. Verify files: `ls ~/.claude/skills/ | grep -E "\.md$" | head -5`
2. Restart Claude Code completely (quit → reopen)
3. Try loading by exact filename: `/skills saas-idea-to-mvp`

**Can't find a skill?**
1. See CHEATSHEET.md for all 65 skill names
2. Use `grep` to search: `ls ~/.claude/skills/ | grep "keyword"`
3. Skills are sorted alphabetically: `ls ~/.claude/skills/ | sort`

**Getting errors when using a skill?**
1. Read the full skill file for context (it's 150-250 lines)
2. Check examples and templates in the skill
3. Try the "Quick Win" section first
4. Refer to the FAQ or troubleshooting section within each skill

---

## Ready to Start?

Pick a skill from the 10 above. Load it now:

```
/skills saas-idea-to-mvp
```

or

```
/skills claude-code-power-user
```

Pick based on what you need RIGHT NOW. Go.
