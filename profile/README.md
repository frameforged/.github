<p align="center">
  <img width="3118" height="3031" alt="frameforged" src="https://github.com/user-attachments/assets/4398dce1-5d8c-4b5c-a1f3-3447f3efb02b" />
</p>

<h1 align="center">frameforged</h1>

<p align="center">
  <strong>No fine-tuning. No training. Just structure.</strong><br/>
  <em>Domain-forged frameworks that turn AI agents into industry experts.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/model-agnostic-465058" alt="Model Agnostic" />
  <img src="https://img.shields.io/badge/format-pure%20markdown-22c55e" alt="Pure Markdown" />
  <img src="https://img.shields.io/badge/setup-minutes-6BD9DE" alt="Setup in minutes" />
  <img src="https://img.shields.io/badge/license-source--available-f59e0b" alt="Source Available" />
</p>

<p align="center">
  <a href="#the-bet-were-making">Why</a> ·
  <a href="#what-is-frameforged">What</a> ·
  <a href="#how-it-works">How</a> ·
  <a href="#the-frameworks">Frameworks</a> ·
  <a href="#get-started-in-90-seconds">Start</a> ·
  <a href="#the-road-ahead">Roadmap</a> ·
  <a href="#your-expertise-belongs-here">Collaborate</a>
</p>

---

## Expertise is the last mile of AI

Ask a frontier model to prepare an EPC construction bid, and it will produce something *reasonable*. Reasonable loses tenders. It doesn't know that profit never gets embedded in unit prices. It doesn't know that a cable-pulling rate below $2 per meter is a red flag, that a missing Price Description file makes the whole estimate meaningless, or that the client's document coding system tells you the discipline before you even open the file.

That knowledge isn't in any training set. It lives in the heads of people who have priced two hundred projects. And it's exactly what separates an answer from a deliverable.

The missing piece isn't intelligence. Intelligence is getting cheaper every quarter. The missing piece is **structure**: the rules, the reference data, the workflows, and the judgment that turn raw capability into professional work.

That's what we forge.

## The bet we're making

Every few months the models get smarter, faster, and cheaper. Most AI products are threatened by that curve, because their moat *is* the model. frameforged is built to ride it:

- **Frameworks compound with every model release.** The same `epc-tender` repository produces better bids on every new model generation, because the domain knowledge doesn't expire. The engine underneath it just gets stronger. Fine-tuned models decay. Structured knowledge appreciates.
- **Agents are becoming the runtime of work.** Claude Code, Cursor, and the growing skills and MCP ecosystem all converge on the same pattern: agents that read files, follow instructions, and operate inside your repository. A frameforged repo *is* that pattern, with `CLAUDE.md` as the operating manual, markdown as the knowledge base, and git as the audit trail.
- **Context engineering is the new fine-tuning.** The industry spent years teaching models. The frontier now is teaching *agents*: giving them the right rules, data, and procedures at the right moment. That is a discipline, and these repositories are what it looks like in practice.

In five years, we believe every serious profession will have its operational knowledge encoded in agent-readable form, the way every serious project has version control today. frameforged exists to build that layer, domain by domain, before anyone else does.

## What is frameforged?

**frameforged** is a collection of source-available, domain-specific frameworks that transform general-purpose AI agents into **operational specialists**.

Each repository is a complete knowledge system:

| Layer | What it contains | What it gives the agent |
|-------|------------------|-------------------------|
| **Rules** | Industry standards, pricing principles, compliance requirements | Knows *how* the work is done |
| **References** | Productivity rates, material prices, benchmark data, all sourced and dated | Works with *real numbers*, not guesses |
| **Templates** | Report structures, checklists, evaluation forms | Produces *consistent, professional output* |
| **Workflows** | Step-by-step procedures, decision trees, validation rules | Follows *proven processes* and verifies its own work |

Drop your project files into the repo, point your AI agent at `CLAUDE.md`, and it works like a seasoned professional instead of a chatbot pretending to be one.

## How it works

```
┌─────────────────┐         ┌──────────────────────┐         ┌─────────────────┐
│                 │         │      THE FORGE       │         │                 │
│  General-       │         │                      │         │  Domain         │
│  Purpose AI     │────────▶│  CLAUDE.md           │────────▶│  Expert         │
│                 │         │  + Rules             │         │                 │
│  Claude / GPT   │         │  + References        │         │  Ready to       │
│  Gemini / local │         │  + Templates         │         │  execute        │
│                 │         │  + Workflows         │         │                 │
└─────────────────┘         └──────────────────────┘         └─────────────────┘
```

1. **Clone** a frameforged repository
2. **Drop** your project files into `projects/`
3. **Open** your AI agent (Claude Code, Cursor, or anything that reads `CLAUDE.md`)
4. **Work.** The agent reads the framework and knows exactly what to do

No API keys. No model training. No vector databases. No complex setup. Just markdown files that give your agent the right context at the right time, with every rule, every rate, and every decision visible in git.

## The frameworks

### Industry operations

Frameworks that execute real commercial work, where the output is measured in money, deadlines, and audits.

| Repository | Domain | Status |
|-----------|--------|--------|
| [**epc-tender**](https://github.com/frameforged/epc-tender) | Oil & Gas EPC bidding. Analyzes multi-package tenders, extracts scope by discipline, prices line items from sourced man-hour and material references, cross-verifies every total, and evaluates incoming bids against benchmarks | ![Active](https://img.shields.io/badge/status-active-22c55e) |
| **supply-chain** | Procurement and logistics. Vendor evaluation, purchase orders, delivery tracking | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |
| **legal-review** | Contract and document analysis. Clause extraction, risk flags, compliance checks | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |
| **financial-reporting** | Audit and compliance. Financial statement analysis, regulatory reporting | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |
| **construction-planning** | Project scheduling. Resource allocation, progress tracking | ![Coming Soon](https://img.shields.io/badge/status-coming%20soon-f59e0b) |

### Knowledge work

Frameworks that industrialize the crafts every team depends on.

| Repository | Domain | Status |
|-----------|--------|--------|
| [**technical-documentation-framework**](https://github.com/frameforged/technical-documentation-framework) | A ten-phase documentation pipeline: product discovery, audience alignment, controlled terminology, natural-voice writing rules, a scored QA rubric, and brand-aware DOCX/PDF delivery with verified output | ![Active](https://img.shields.io/badge/status-active-22c55e) |
| [**presentation-framework**](https://github.com/frameforged/presentation-framework) | Multi-agent presentation production. Eight specialist agents research the topic, structure the narrative, plan slides, write content, and run quality control before anything ships | ![Active](https://img.shields.io/badge/status-active-22c55e) |

> Have a domain in mind? [Open a discussion](https://github.com/orgs/frameforged/discussions). The next framework on the roadmap might be yours.

## Get started in 90 seconds

```bash
# Clone the framework you need
git clone https://github.com/frameforged/epc-tender.git
cd epc-tender

# Drop your project files
cp -r ~/Downloads/my-tender-docs projects/my-project/

# Open Claude Code (or any agent that reads CLAUDE.md)
claude

# Tell it what to do
> Analyze the tender in projects/my-project
```

That's it. The agent reads `CLAUDE.md`, loads the domain rules, checks the reference data, follows the workflow, and produces output a professional can sign.

### Anatomy of a framework

Every frameforged repository follows the same architecture, so learning one means learning them all:

```
your-framework/
├── CLAUDE.md              # Entry point, the agent's operating manual
├── README.md              # Human documentation
│
├── references/            # Domain knowledge base
│   ├── rules.md           # Industry rules and principles
│   ├── rates.md           # Benchmark data, pricing, rates (sourced & dated)
│   └── standards.md       # Technical standards and codes
│
├── templates/             # Output templates
│   ├── analysis.md        # Analysis report structure
│   ├── checklist.md       # Evaluation checklist
│   └── comparison.md      # Comparison matrix
│
├── projects/              # Active work (your files go here)
│   └── [project-name]/
│
└── archive/               # Completed work, with outcomes
    └── [project-result]/
```

`CLAUDE.md` defines what role the agent plays, which files it reads and when, what workflow it follows, what output it produces, and which rules it must never break. Think of it as the job description, the training manual, and the quality gate in one file the agent actually reads.

## Philosophy

### Why structure beats training

| Approach | Cost | Time | Flexibility | Longevity |
|----------|------|------|-------------|-----------|
| Fine-tuning a model | $$$ | Weeks | Low, locked to training data | Degrades as models move on |
| RAG pipeline | $$ | Days | Medium, needs infra | Depends on retrieval quality |
| **frameforged** | Free | Minutes | High, edit a markdown file | **Improves with every model release** |

Frameworks are **transparent** (every rule is readable), **versionable** (git tracks every decision), **portable** (any agent that reads files), **collaborative** (teams review and improve them like code), and **auditable** (every pricing choice and methodology is documented, which matters when the output is a bid worth millions).

### The forge metaphor

Raw metal is strong but shapeless. A forge doesn't change what the metal *is*. It shapes it into something useful. That's what frameforged does to AI agents. The intelligence is already there. We give it the right shape for the job.

## The road ahead

Where this is going, in order:

- **Template repository.** A scaffold so any domain expert can forge a new framework in an afternoon, with structure, examples, and a validation checklist included.
- **New industry domains.** Supply chain, legal review, financial reporting, and construction planning are next. The queue after that is driven by [community discussions](https://github.com/orgs/frameforged/discussions).
- **Framework test harnesses.** Reference scenarios with known-good outputs, so a change to a rule or a rate can be verified the way code is verified.
- **Deeper agent integration.** First-class support for the emerging skills and MCP ecosystem, multi-agent orchestration patterns (the presentation framework already runs eight agents in sequence), and structured hand-offs between frameworks.
- **Localization.** Regional rates, local standards, and translated frameworks, because a man-hour in Sumgayit is not a man-hour in Rotterdam.

The long game: **a forged framework for every profession**. A living, versioned, community-maintained knowledge layer that any agent, present or future, can pick up and use. Models will keep changing. This layer is what makes each new one immediately useful.

## Your expertise belongs here

The best frameworks aren't built by AI engineers. They're built by **people who do the actual work**. A construction estimator who has priced 200 projects knows things no language model ever will. A procurement specialist who has negotiated 500 contracts carries knowledge no training dataset captures.

frameforged is designed so you can contribute that knowledge **without writing a single line of code**. You're not editing markdown files. You're encoding operational intelligence, and making sure decades of hard-won expertise don't retire when people do.

**Three ways in:**

1. **Forge a new domain.** Structure what you know into `references/`, `templates/`, and a `CLAUDE.md`. Test it on real project files, then [open a discussion](https://github.com/orgs/frameforged/discussions) to get it listed. Start with one workflow, the community helps you grow it.
2. **Strengthen an existing framework.** Add a missing rate, update an outdated standard, refine a template, cover an edge case, localize for your region.
3. **Share what you know.** [Open a discussion](https://github.com/orgs/frameforged/discussions) about how your industry actually works, [report inaccuracies](https://github.com/frameforged/epc-tender/issues), or review a framework in your specialty and flag what's missing.

### Contribution principles

| Principle | What it means |
|-----------|--------------|
| **Domain accuracy first** | Every rate, rule, and reference must be sourced and current. When in doubt, cite the standard. |
| **Write for two audiences** | Frameworks are read by AI agents *and* humans. Clear, simple language wins. |
| **One concept, one file** | A file about pricing doesn't drift into scheduling. |
| **Test with real work** | A framework that doesn't produce professional output on actual project files isn't ready. |
| **Protect confidentiality** | No proprietary data, client information, or internal pricing. Ever. |

## About

**frameforged** is an initiative by [**nanelimon.ai**](https://nanelimon.ai), a team contributing to open source since 2021 and building at the intersection of AI agents and real-world industry operations.

We started frameforged because we kept seeing the same gap: powerful agents producing generic output that professionals couldn't sign their name under. Domain frameworks built by experts, refined by a community, and versioned like code are the fastest and most durable way to close that gap. Not for one model generation. For all of them.

## License

**frameforged** is **source-available**, not open-source. You can view, study, and evaluate everything. Usage requires registration.

| Usage type | Allowed? | Requirement |
|-----------|----------|-------------|
| **Viewing & studying** | Yes | None |
| **Personal / non-commercial use** | Yes | Registration (free) |
| **Commercial use** | By permission | Commercial license |
| **Redistribution / resale** | No | Not permitted |
| **Contributing** (PRs, issues) | Yes | CLA accepted on submission |

**To register**, email **support@nanelimon.ai** with your name or organization, the repository you want to use, and your intended use case. We'll confirm and you're good to go.

**Why not fully open-source?** Every framework carries real domain expertise from engineers, lawyers, and analysts. A fully permissive license would let that work be rebranded and resold with nothing returned. Our license keeps the frameworks accessible to the community, protects contributors' attribution, and lets commercial users fund the next domains.

Full terms: [LICENSE](https://github.com/frameforged/.github/blob/main/LICENSE)

---

<p align="center">
  <strong>The intelligence is already there. We just give it the right shape.</strong><br/><br/>
  Copyright (c) 2021-present <a href="https://nanelimon.ai">nanelimon.ai</a>. All rights reserved.<br/><br/>
  <a href="https://github.com/frameforged">GitHub</a> · <a href="https://nanelimon.ai">nanelimon.ai</a> · <a href="mailto:support@nanelimon.ai">support@nanelimon.ai</a>
</p>
