<p align="center">
  <img width="3118" height="3031" alt="Adsız tasarım (7)" src="https://github.com/user-attachments/assets/4398dce1-5d8c-4b5c-a1f3-3447f3efb02b" />
</p>

<h1 align="center">frameforged</h1>

<p align="center">
  <strong>No fine-tuning. No training. Just structure.</strong><br/>
  <em>Domain-forged frameworks that turn AI agents into industry experts.</em>
</p>

<p align="center">
  <a href="#what-is-frameforged">What</a> · <a href="#how-it-works">How</a> · <a href="#repositories">Repos</a> · <a href="#get-started">Start</a> · <a href="#collaboration">Collaborate</a>
</p>

---

## The Problem

AI agents are incredibly capable — but they're generalists. Ask Claude to prepare an EPC construction bid, review a procurement contract, or audit a financial report, and it will give you a *reasonable* answer. But reasonable isn't good enough when millions of dollars are on the line.

The missing piece isn't intelligence. It's **structure**.

## What is frameforged?

**frameforged** is a collection of source-available, domain-specific frameworks that transform general-purpose AI agents into **operational specialists**.

Each repository is a complete knowledge system:

| Layer | What It Contains | Why It Matters |
|-------|-----------------|----------------|
| **Rules** | Industry standards, pricing principles, compliance requirements | The agent knows *how* to work |
| **References** | Productivity rates, material prices, benchmark data | The agent has *real data* to work with |
| **Templates** | Report structures, checklists, evaluation forms | The agent produces *consistent output* |
| **Workflows** | Step-by-step procedures, decision trees, validation rules | The agent follows *proven processes* |

The result? Drop your project files into the repo, point your AI agent at `CLAUDE.md`, and it works like a seasoned professional — not a chatbot pretending to be one.

## How It Works

```
┌─────────────────┐         ┌──────────────────────┐         ┌─────────────────┐
│                 │         │     THE  FORGE       │         │                 │
│  General-       │         │                      │         │  Domain         │
│  Purpose AI     │────────>│  CLAUDE.md           │────────>│  Expert         │
│                 │         │  + Rules             │         │                 │
│  Claude / GPT   │         │  + References        │         │  Ready to       │
│  Gemini / etc.  │         │  + Templates         │         │  execute tasks  │
│                 │         │  + Workflows         │         │                 │
└─────────────────┘         └──────────────────────┘         └─────────────────┘
```

1. **Clone** a frameforged repository
2. **Drop** your project files into the designated folder
3. **Open** your AI agent (Claude Code, Cursor, etc.)
4. **Work** — the agent reads `CLAUDE.md` and knows exactly what to do

No API keys. No model training. No vector databases. No complex setup.

Just markdown files that give your AI agent the right context at the right time.

## Repositories

| Repository | Domain | Status |
|-----------|--------|--------|
| [**epc-tender**](https://github.com/frameforged/epc-tender) | Oil & Gas EPC Bidding — analyze tenders, prepare cost estimates, evaluate proposals | ![Active](https://img.shields.io/badge/status-active-22c55e) |
| **supply-chain** | Procurement & Logistics — vendor evaluation, purchase orders, delivery tracking | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |
| **legal-review** | Contract & Document Analysis — clause extraction, risk flags, compliance checks | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |
| **financial-reporting** | Audit & Compliance — financial statement analysis, regulatory reporting | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |
| **construction-planning** | Project Scheduling — resource allocation, Gantt charts, progress tracking | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |

> Have a domain in mind? [Open a discussion](https://github.com/orgs/frameforged/discussions) — we'd love to hear what you need.

## Get Started

### Using an existing framework

```bash
# Clone the framework you need
git clone https://github.com/frameforged/epc-tender.git
cd epc-tender

# Drop your project files
cp -r ~/Downloads/my-tender-docs projects/my-project/

# Open Claude Code (or any AI agent that reads CLAUDE.md)
claude

# Tell it what to do
> Analyze the tender in projects/my-project
```

That's it. The agent reads `CLAUDE.md`, understands the domain rules, references the knowledge base, and produces professional-grade output.

### Building your own framework

Every frameforged repository follows the same architecture:

```
your-framework/
├── CLAUDE.md              # Entry point — the agent reads this first
├── README.md              # Human documentation
│
├── references/            # Domain knowledge base
│   ├── rules.md           # Industry rules and principles
│   ├── rates.md           # Benchmark data, pricing, rates
│   └── standards.md       # Technical standards and codes
│
├── templates/             # Output templates
│   ├── analysis.md        # Analysis report structure
│   ├── checklist.md       # Evaluation checklist
│   └── comparison.md      # Comparison matrix
│
├── projects/              # Active work (user drops files here)
│   └── [project-name]/
│
└── archive/               # Completed work
    └── [project-result]/
```

The key is `CLAUDE.md` — this is where you define:
- What role the agent plays
- What files it should read and when
- What workflow it should follow
- What output it should produce
- What rules it must respect

Think of `CLAUDE.md` as the operating manual for your AI agent in a specific domain.

## Philosophy

### Why structure beats training

| Approach | Cost | Time | Flexibility | Accuracy |
|----------|------|------|-------------|----------|
| Fine-tuning a model | $$$ | Weeks | Low — locked to training data | Degrades over time |
| RAG pipeline | $$ | Days | Medium — needs vector DB | Depends on retrieval |
| **frameforged** | Free | Minutes | High — edit markdown files | Always current |

Frameworks are:
- **Transparent** — every rule, every reference, every template is readable markdown
- **Versionable** — git tracks every change, every decision, every update
- **Portable** — works with any AI agent that reads files (Claude, GPT, Gemini, local models)
- **Collaborative** — teams can review, discuss, and improve frameworks together
- **Auditable** — every pricing decision, every methodology choice is documented

### The forge metaphor

Raw metal is strong but shapeless. A forge doesn't change what the metal *is* — it shapes it into something *useful*. That's exactly what frameforged does to AI agents. The intelligence is already there. We just give it the right shape for the job.

## Collaboration

The best frameworks aren't built by AI engineers — they're built by **people who do the actual work**. A construction estimator who has priced 200 projects knows things no language model ever will. A procurement specialist who has negotiated 500 contracts carries knowledge that no training dataset captures.

**frameforged needs that knowledge.** And we've designed the entire system so you can contribute it — without writing a single line of code.

### Why your expertise matters

AI models are trained on public internet data. They know *about* industries. But they don't know the unwritten rules — the pricing logic that only makes sense after years on the job, the red flags in a tender document that textbooks never mention, the workflow shortcuts that separate a junior from a senior.

When you contribute to frameforged, you're not just editing markdown files. You're encoding **operational intelligence** that makes AI agents genuinely useful for professionals in your field. Every rule you add, every reference table you update, every template you refine — it directly shapes how thousands of AI agents behave in real-world scenarios.

### How to contribute

#### Build a new domain framework

You're a domain expert — a civil engineer, a supply chain analyst, a legal professional, a financial auditor, or anyone with deep operational knowledge. Here's how to turn that into a framework:

1. Fork the [template repository](https://github.com/frameforged/template) *(coming soon)*
2. Structure your knowledge into `references/`, `templates/`, and `CLAUDE.md`
3. Test it against real-world scenarios — give it actual project files and see if the output is professional-grade
4. [Open a discussion](https://github.com/orgs/frameforged/discussions) or submit a PR to get it listed

You don't need to build everything at once. Start with one workflow, one set of rules, one template. The community will help you expand it.

#### Strengthen an existing framework

Every framework has gaps — a missing productivity rate, an outdated standard, a scenario that wasn't covered. If you spot one, fix it:

- **Add reference data** — material prices, labor rates, benchmark figures from your region or specialty
- **Refine templates** — improve report structures, add evaluation criteria, create new checklists
- **Expand workflows** — cover edge cases, add decision branches, document exception handling
- **Update standards** — regulations change, codes get revised, best practices evolve
- **Localize** — translate frameworks or adapt them to regional standards and practices

#### Share domain knowledge

Not ready to write a full framework? Your knowledge is still valuable:

- [Open a discussion](https://github.com/orgs/frameforged/discussions) to share how your industry works — what an AI agent *should* know to be useful
- [Report issues](https://github.com/frameforged/epc-tender/issues) when you spot inaccuracies, missing context, or wrong assumptions
- Suggest new domains that would benefit from structured frameworks
- Review existing frameworks from your area of expertise and flag what's missing

### Contribution principles

| Principle | What it means |
|-----------|--------------|
| **Domain accuracy first** | Every rate, rule, and reference must be sourced and current. When in doubt, cite the standard. |
| **Write for two audiences** | Frameworks are read by AI agents *and* humans. Clear, simple language wins. |
| **One concept, one file** | Keep files focused. A file about pricing shouldn't drift into scheduling. |
| **Test with real work** | A framework that doesn't produce professional output on actual project files isn't ready. |
| **Protect confidentiality** | Never include proprietary data, client information, internal pricing, or anything that shouldn't be public. |

### The bigger picture

Every industry has decades of accumulated knowledge sitting in the heads of experienced professionals. Most of it never gets documented — it's passed down through mentorship, learned through trial and error, or simply lost when people move on.

frameforged is a way to **capture and structure that knowledge** so it doesn't disappear. When you contribute, you're not just helping an AI agent — you're building a shared knowledge base that makes your entire industry more accessible, more transparent, and more efficient.

> **No coding required. No AI expertise needed. Just your domain knowledge, structured in a way that machines — and humans — can use.**

## About

**frameforged** is an initiative by [**nanelimon.ai**](https://nanelimon.ai) — a team that has been contributing to open-source projects since 2021. We build tools and frameworks at the intersection of artificial intelligence and real-world industry operations.

We started frameforged because we saw a gap: AI agents are powerful, but without the right structure, they produce generic output that professionals can't rely on. We believe that domain frameworks — built by experts, refined by the community — are the fastest way to make AI genuinely useful in specialized fields.

## License

**frameforged** is **source-available**, not open-source. You can view, study, and evaluate the code — but usage requires registration and permission.

| Usage Type | Allowed? | Requirement |
|-----------|----------|-------------|
| **Viewing & studying** the code | Yes | None |
| **Personal / non-commercial use** | Yes | Registration required |
| **Commercial use** | By permission only | Commercial license required |
| **Redistribution / resale** | No | Not permitted |
| **Contributing** (PRs, issues) | Yes | CLA accepted on submission |

### How to register

Send an email to **support@nanelimon.ai** with:
- Your name or organization
- Which repository you want to use
- Your intended use case

We'll confirm your registration and you're good to go.

### Why not fully open-source?

We invest significant domain expertise — real-world industry knowledge from engineers, lawyers, and analysts — into every framework. A fully permissive license would allow others to take that work, rebrand it, and sell it without giving anything back. Our license ensures:

- The **community** can always access and learn from the frameworks
- **Contributors** get proper attribution and their work is protected
- **Commercial users** support the project's sustainability
- **nanelimon.ai** can continue investing in new domains

Full license terms: [LICENSE](https://github.com/frameforged/.github/blob/main/LICENSE)

---

<p align="center">
  <strong>The intelligence is already there. We just give it the right shape.</strong><br/><br/>
  Copyright (c) 2021-present <a href="https://nanelimon.ai">nanelimon.ai</a> — All rights reserved.<br/><br/>
  <a href="https://github.com/frameforged">GitHub</a> · <a href="https://nanelimon.ai">nanelimon.ai</a> · <a href="mailto:support@nanelimon.ai">support@nanelimon.ai</a>
</p>
