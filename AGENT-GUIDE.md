# Claude Skills 360 — Agent Guide

Master the 20 autonomous agents and learn when to deploy them.

## What Are Agents? (Skills vs. Agents)

### Skills
**Skills** are reusable knowledge bases. They teach you HOW to do something.

Example: "affiliate-site-generator" teaches you the framework to build a niche content site.

```
/skills affiliate-site-generator
```
→ You read, you plan, you execute.

### Agents
**Agents** are autonomous workers that DO things with multiple skills. They think, plan, and act without waiting for feedback.

Example: "content-engine-agent" automatically researches keywords, generates outlines, writes articles, and optimizes them — all in one go.

```
/agents content-engine-agent
```
→ Agent reads the request, invokes skills, makes decisions, and delivers results.

### Key Difference

| Aspect | Skills | Agents |
|--------|--------|--------|
| **You are** | The executor | The director |
| **Input** | Your effort (step-by-step) | Your goals (one sentence) |
| **Output** | Knowledge + templates | Finished work |
| **Interaction** | Read and adapt | Monitor and refine |
| **Best for** | Learning, customization | Repetitive tasks, speed |

---

## The 20 Agents at a Glance

### Marketing & Demand Generation (3 agents)

**1. SEO Audit Agent**
**What it does**: Audits entire websites for technical health, content gaps, and competitive positioning.
**Invocation**: `/agents seo-audit-agent`
**Input**: Website URL
**Output**: Audit report with prioritized fixes (technical, content, authority)
**Real workflow**:
```
Request: "Audit my site for SEO issues"
Agent:
1. Crawls entire domain
2. Analyzes Core Web Vitals
3. Identifies thin pages and keyword cannibalization
4. Benchmarks against competitors
5. Produces prioritized action roadmap
```

**2. Ad Campaign Agent**
**What it does**: Creates, optimizes, and manages paid advertising campaigns across platforms.
**Invocation**: `/agents ad-campaign-agent`
**Input**: Campaign goals, budget, target audience
**Output**: Campaign structure (ads, targeting, budget allocation, creative)
**Real workflow**:
```
Request: "Build a $5k/month Google Ads campaign for saas leads"
Agent:
1. Defines campaign structure (TOFU/MOFU/BOFU)
2. Recommends keywords and bid strategy
3. Generates ad copy variations
4. Sets up conversion tracking
5. Creates launch checklist
```

**3. Content Engine Agent**
**What it does**: Researches, generates, and optimizes content at scale.
**Invocation**: `/agents content-engine-agent`
**Input**: Topic, target audience, content type (blog, guides, case studies)
**Output**: Outline, draft, optimized version, and distribution plan
**Real workflow**:
```
Request: "Create 5 SEO-optimized blog posts about remote team management"
Agent:
1. Research top-ranking competitors
2. Extract keyword opportunities
3. Generate content outline with internal links
4. Write full articles with CTAs
5. Optimize for on-page SEO
6. Generate social media snippets
```

---

### Sales & Growth (3 agents)

**4. Sales Automator Agent**
**What it does**: Automates prospecting, email sequences, and deal management.
**Invocation**: `/agents sales-automator-agent`
**Input**: Target audience, offer, campaign duration
**Output**: Email sequences, follow-up cadence, deal tracking
**Real workflow**:
```
Request: "Create a 7-email prospecting sequence for B2B services"
Agent:
1. Researches target persona pain points
2. Writes hook email (high open rate)
3. Generates value-add emails (sequence 2-5)
4. Creates objection-handling emails
5. Designs follow-up cadence (timing and triggers)
6. Builds reply filters and tracking
```

**5. Email Marketing Agent**
**What it does**: Designs, writes, and optimizes email campaigns.
**Invocation**: `/agents email-marketing-agent`
**Input**: Campaign goal, audience, offer
**Output**: Email copy, template design, send strategy, A/B tests
**Real workflow**:
```
Request: "Build a product launch email campaign"
Agent:
1. Segments audience by engagement level
2. Writes teaser email
3. Creates launch announcement
4. Generates follow-up sequence
5. Designs welcome series for new subscribers
6. Proposes A/B tests (subject lines, CTAs)
```

**6. Brand Builder Agent**
**What it does**: Creates or refreshes brand identity from scratch.
**Invocation**: `/agents brand-builder-agent`
**Input**: Business type, target market, brand personality
**Output**: Brand guidelines (colors, fonts, voice, messaging)
**Real workflow**:
```
Request: "Build a brand for my sustainable fashion startup"
Agent:
1. Researches competitor branding
2. Defines brand archetype (rebel, sage, hero, etc.)
3. Recommends color palettes (psychology + trends)
4. Selects typography (headings, body)
5. Writes brand voice guidelines
6. Creates messaging framework
```

---

### Development & Code (4 agents)

**7. Code Review Agent**
**What it does**: Analyzes code for quality, security, and best practices.
**Invocation**: `/agents code-review-agent`
**Input**: Code repository or file
**Output**: Issue report, fixes, refactoring suggestions
**Real workflow**:
```
Request: "Review my Next.js codebase for performance and security"
Agent:
1. Scans for security vulnerabilities
2. Identifies performance bottlenecks
3. Flags code smell (duplication, complexity)
4. Checks for missing tests
5. Recommends refactoring (with examples)
6. Grades code quality (A-F)
```

**8. Database Architect Agent**
**What it does**: Designs database schemas and optimizes queries.
**Invocation**: `/agents database-architect-agent`
**Input**: Application requirements, data model, scale
**Output**: ER diagram, schema, indexes, migration plan
**Real workflow**:
```
Request: "Design a database for a marketplace with users, products, and orders"
Agent:
1. Creates normalized schema
2. Defines relationships and constraints
3. Recommends indexes for query performance
4. Generates migration script
5. Proposes caching strategy
6. Creates backup/recovery plan
```

**9. Deployment Agent**
**What it does**: Automates code deployment, environment setup, and infrastructure.
**Invocation**: `/agents deployment-agent`
**Input**: Application stack, deployment target, environment
**Output**: Deploy script, infrastructure config, rollback plan
**Real workflow**:
```
Request: "Deploy my React app to production on Vercel"
Agent:
1. Creates deployment pipeline (CI/CD)
2. Sets up environment variables
3. Configures CDN caching
4. Generates health checks
5. Creates rollback procedures
6. Documents deployment runbook
```

**10. Security Auditor Agent**
**What it does**: Audits applications and infrastructure for security vulnerabilities.
**Invocation**: `/agents security-auditor-agent`
**Input**: Application URL or codebase
**Output**: Vulnerability report, fix recommendations, compliance checklist
**Real workflow**:
```
Request: "Security audit my web application"
Agent:
1. Scans for OWASP Top 10 issues
2. Tests authentication/authorization
3. Checks data encryption
4. Identifies API vulnerabilities
5. Verifies dependency security (npm audit)
6. Rates security posture
```

---

### Product & Research (3 agents)

**11. Product Manager Agent**
**What it does**: Manages product development from concept to launch.
**Invocation**: `/agents product-manager-agent`
**Input**: Product idea, target market, resources
**Output**: PRD (Product Requirements Document), roadmap, success metrics
**Real workflow**:
```
Request: "Create a PRD for a task management app for remote teams"
Agent:
1. Defines product vision and positioning
2. Identifies user personas and use cases
3. Maps core features and MVP scope
4. Creates wireframe descriptions
5. Defines success metrics (KPIs)
6. Plans 12-month roadmap
```

**12. Research Desk Agent**
**What it does**: Conducts deep research and synthesizes findings.
**Invocation**: `/agents research-desk-agent`
**Input**: Research question or topic
**Output**: Comprehensive report with sources, insights, and recommendations
**Real workflow**:
```
Request: "Research the market for AI-powered email tools"
Agent:
1. Identifies competitors and their features
2. Analyzes pricing and positioning
3. Researches customer pain points (reviews, forums)
4. Gathers market size and growth data
5. Identifies white space opportunities
6. Produces actionable intelligence report
```

**13. Competitor Intel Agent**
**What it does**: Analyzes competitors and identifies competitive advantages.
**Invocation**: `/agents competitor-intel-agent`
**Input**: Your product/service + competitor list
**Output**: Competitive analysis matrix, differentiation strategy
**Real workflow**:
```
Request: "Analyze competitors for my SaaS product"
Agent:
1. Documents features and pricing
2. Evaluates user experience
3. Analyzes marketing and positioning
4. Identifies gaps and weaknesses
5. Recommends differentiation angle
6. Produces battle card for sales
```

---

### Content & Media (2 agents)

**14. Podcast Video Agent**
**What it does**: Scripts and produces podcast episodes and videos.
**Invocation**: `/agents podcast-video-agent`
**Input**: Topic, target audience, format (podcast/video)
**Output**: Script, episode outline, production notes
**Real workflow**:
```
Request: "Create a podcast episode about AI business automation"
Agent:
1. Researches trending angles
2. Structures episode (intro, segments, CTA)
3. Writes engaging script
4. Suggests guest(s) or expert quotes
5. Creates show notes with timestamps
6. Generates social media clips
```

**15. GraphRAG Builder Agent**
**What it does**: Builds knowledge graphs for semantic search and AI retrieval.
**Invocation**: `/agents graphrag-builder-agent`
**Input**: Document corpus or knowledge base
**Output**: Knowledge graph schema, entity extraction, relation mapping
**Real workflow**:
```
Request: "Build a knowledge graph from our internal documentation"
Agent:
1. Extracts entities (concepts, people, tools)
2. Maps relationships (uses, related_to, etc.)
3. Identifies key topics and clusters
4. Generates graph schema
5. Creates semantic search indexes
6. Builds query interface
```

---

### Operations & Automation (2 agents)

**16. Workflow Automator Agent**
**What it does**: Automates business processes and repetitive tasks.
**Invocation**: `/agents workflow-automator-agent`
**Input**: Repetitive task description
**Output**: Automation workflow, trigger/action pairs, error handling
**Real workflow**:
```
Request: "Automate our lead qualification process"
Agent:
1. Maps current manual steps
2. Defines qualification criteria
3. Recommends tools (Zapier, n8n, custom API)
4. Creates workflow diagram
5. Sets up scoring/routing logic
6. Builds notifications and handoffs
```

**17. Client Onboarding Agent**
**What it does**: Designs and implements client onboarding sequences.
**Invocation**: `/agents client-onboarding-agent`
**Input**: Business type, service delivery model
**Output**: Onboarding sequence, welcome kit, success metrics
**Real workflow**:
```
Request: "Create a client onboarding process for a marketing agency"
Agent:
1. Designs kickoff call agenda
2. Creates welcome email sequence
3. Generates client intake form
4. Builds project setup checklist
5. Drafts communication plan
6. Creates 30/60/90 success metrics
```

---

### Finance & Legal (2 agents)

**18. Financial Analyst Agent**
**What it does**: Analyzes financial data, forecasts, and identifies opportunities.
**Invocation**: `/agents financial-analyst-agent`
**Input**: Financial data (revenue, expenses, metrics)
**Output**: Analysis, forecasts, recommendations
**Real workflow**:
```
Request: "Analyze my business finances and recommend cost cuts"
Agent:
1. Reviews revenue trends
2. Categories and analyzes expenses
3. Identifies cost reduction opportunities
4. Projects cash flow
5. Recommends pricing optimization
6. Creates financial dashboard
```

**19. Tax Finance Agent**
**What it does**: Provides tax strategies, deduction tracking, and financial planning.
**Invocation**: `/agents tax-finance-agent`
**Input**: Income, expenses, business structure
**Output**: Tax strategy, deduction checklist, planning recommendations
**Real workflow**:
```
Request: "Optimize my taxes for a freelance consulting business"
Agent:
1. Reviews business structure (S-Corp vs. LLC)
2. Identifies deductible expenses
3. Tracks quarterly tax payments
4. Recommends retirement plan options
5. Suggests tax-loss harvesting strategies
6. Creates tax planning calendar
```

**20. Legal Document Agent**
**What it does**: Generates, reviews, and customizes legal documents.
**Invocation**: `/agents legal-document-agent`
**Input**: Document type, parties involved
**Output**: Document template, customized version, review notes
**Real workflow**:
```
Request: "Generate a service agreement for my consulting practice"
Agent:
1. Creates contract structure
2. Defines scope, payment terms, liability
3. Adds intellectual property clauses
4. Includes termination and dispute resolution
5. Flags legal considerations
6. Produces ready-to-sign document
```

---

## How to Invoke Agents

### Basic Invocation

```
/agents agent-name
```

Example:
```
/agents seo-audit-agent
```

The agent will load and describe its capabilities, inputs, and expected outputs.

### Providing Context

Most agents work best when you provide context:

```
/agents agent-name
[Follow the prompts or provide your specific request]

Example: "I want to audit my e-commerce site for SEO issues"
```

### Multi-Step Agent Workflows

Agents often work best across multiple interactions:

1. **Initial Setup**: Load agent and provide overview
2. **Input Data**: Supply specifics (URLs, data, goals)
3. **Agent Planning**: Agent outlines its approach
4. **Execution**: Agent performs analysis/generation
5. **Review & Refine**: You review output and ask for iterations

---

## Real-World Agent Workflows

### Example 1: Launch a Marketing Campaign

**Goal**: Launch a Google Ads campaign for a B2B SaaS product.

**Step 1**: Load ad campaign agent
```
/agents ad-campaign-agent
Input: "B2B SaaS, $5k/month budget, target IT managers"
```

**Step 2**: Agent produces campaign structure
- Keyword research and bid strategy
- Ad copy variations (3-5 versions)
- Landing page recommendations
- Conversion tracking setup

**Step 3**: Review and ask for iterations
```
"Can you add more aggressive top-of-funnel keywords?"
"What's the expected CPC for this market?"
```

**Step 4**: Launch
Agent produces:
- Campaign setup checklist
- Ad group structure
- Negative keyword list
- Weekly monitoring checklist

**Total time**: 2-3 hours (agent handles 80%, you review and launch)

---

### Example 2: Build a Product

**Goal**: Take a product idea from concept to PRD and launch plan.

**Step 1**: Load product manager agent
```
/agents product-manager-agent
Input: "AI-powered task manager for remote teams"
```

**Step 2**: Agent researches and produces
- Market analysis and positioning
- User personas and use cases
- MVP feature list
- Wireframe descriptions
- Success metrics

**Step 3**: Collaborate on refinement
```
"Remove calendar integration from MVP scope"
"Add export to CSV as a must-have feature"
```

**Step 4**: Agent produces launch assets
- Full PRD document
- 12-month roadmap
- Go-to-market strategy
- Competitive positioning

**Total time**: 4-6 hours (vs. 2-3 days doing it manually)

---

### Example 3: Security Audit Your App

**Goal**: Identify and fix security vulnerabilities.

**Step 1**: Load security auditor agent
```
/agents security-auditor-agent
Input: "Node.js/React app with user authentication"
```

**Step 2**: Agent performs comprehensive audit
- OWASP Top 10 scan
- Authentication/authorization review
- Data protection assessment
- Dependency vulnerability check

**Step 3**: Review findings and prioritize
Agent provides:
- Critical issues (fix immediately)
- High-priority issues (fix this sprint)
- Medium issues (backlog)
- Low issues (monitor)

**Step 4**: Get fixes from agent
```
"Generate fix for the SQL injection vulnerability"
"Create secure password reset flow"
```

**Total time**: 3-4 hours (comprehensive security review)

---

## Agent Best Practices

### 1. Load the Right Agent for Your Task

Don't try to use one agent for everything. Match task to agent:

| Task | Agent |
|------|-------|
| "I need SEO help" | SEO Audit Agent |
| "I need Google Ads set up" | Ad Campaign Agent |
| "I need blog posts" | Content Engine Agent |
| "I need to review my code" | Code Review Agent |
| "I need a PRD" | Product Manager Agent |

### 2. Provide Clear Input

Agents work best with specific, detailed input:

**Bad**: "Do something with marketing"
**Good**: "Create a Google Ads campaign targeting IT managers, budget $5k/month, goal is demo requests"

**Bad**: "Review my code"
**Good**: "Review my Next.js codebase for performance issues and security vulnerabilities"

### 3. Iterate, Don't Accept First Draft

Agents produce good work, but refine it:

```
Agent output: [5 blog post outlines]
You: "Can you make these more actionable? Add more examples."
Agent: [Revised outlines with 10+ examples each]
You: "Perfect. Now write the first article."
```

### 4. Combine Agents for Complex Tasks

No single agent handles everything. Combine them:

**Launch a new product**:
1. Product Manager Agent → PRD
2. Content Engine Agent → Marketing content
3. Ad Campaign Agent → Advertising strategy
4. Sales Automator Agent → Sales outreach

**Redesign your website**:
1. Brand Builder Agent → Brand refresh
2. SEO Audit Agent → Current site analysis
3. Content Engine Agent → New content
4. Code Review Agent → Code quality check

### 5. Save and Reuse Agent Outputs

Agents produce valuable artifacts:
- Campaign structures (reuse for next campaign)
- Content outlines (template for future content)
- Code reviews (checklist for future PRs)
- PRDs (template for next product)

Save these and reference them.

### 6. Monitor Agent Decisions

Agents make logical decisions, but you're the CEO:
- Accept what's right ✓
- Challenge what doesn't fit your business ✗
- Ask for alternatives when uncertain ❓

---

## When to Use Skills vs. Agents

### Use Skills When...
- You're learning a new area
- You want to understand the "why"
- You need customized approaches
- You're teaching someone else
- You have time for deep work

### Use Agents When...
- You need results fast
- Task is repetitive (you've done it before)
- You want to focus on decisions, not execution
- You're outsourcing to your AI assistant
- You have multiple projects in parallel

**Pro Tip**: Use skills FIRST to understand the domain, then use agents to execute at scale.

---

## Advanced: Combining Agents with Skills

### Workflow: Build a Complete Website

**Phase 1: Planning (Use Skills)**
- Load `/skills claude-md-architect` → Design your site structure
- Load `/skills vibe-coding-patterns` → Pick your development approach

**Phase 2: Brand (Use Agent)**
- Load `/agents brand-builder-agent` → Create visual identity

**Phase 3: Content (Use Agent)**
- Load `/agents content-engine-agent` → Create core pages

**Phase 4: Code (Use Agents)**
- Load `/agents code-review-agent` → Review code quality
- Load `/agents deployment-agent` → Plan deployment

**Phase 5: Launch (Use Agents)**
- Load `/agents ad-campaign-agent` → Create launch ads
- Load `/agents email-marketing-agent` → Build launch email sequence

**Total time**: 2-3 weeks (vs. 8-12 weeks doing it all manually)

---

## Troubleshooting Agents

### "Agent not found" or "Can't load agent"

Check that agent files are in `~/.claude/agents/`:
```bash
ls ~/.claude/agents/ | grep agent-name
```

Restart Claude Code and try again.

### "Agent output is generic/unhelpful"

Provide more context:
- **Instead of**: "Audit my site"
- **Try**: "Audit my e-commerce site for SEO. We target high-volume keywords in fitness equipment. Top competitors: [names]. Current traffic: 5k/month."

More specifics = better output.

### "Agent is taking too long"

Some agents are thorough (5-30 min for comprehensive work). This is normal. If it's truly stuck:
1. Stop the agent
2. Reload and try a smaller scope
3. Break into smaller tasks

### "Output needs refinement"

Agents produce drafts. Refine them:

```
/agents agent-name
[Get output]
"That's good, but can you also [specific ask]?"
```

Iteration is part of the workflow.

---

## Next Steps

1. **Pick 3 agents** matching your biggest challenges
2. **Load each one** and read their capabilities
3. **Try the first one** on a real task this week
4. **Iterate on output** until it meets your needs
5. **Combine with skills** for even more power

When you're ready for automation at scale, read **SWARM-GUIDE.md** to orchestrate multiple agents together.

---

**Start now**:
```
/agents seo-audit-agent
```

or

```
/agents content-engine-agent
```

Pick based on what you need today.
