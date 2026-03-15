# Marketing Prompts for Founders

**Get your first customers this week.** Clone this repo, type one command, answer 3 questions about your product, and get a complete marketing playbook built for your situation — cold emails, landing page copy, launch plan, pricing strategy, whatever you need right now.

Built for solo technical founders who'd rather ship code than read marketing blogs.

Based on [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders) by [@e_stradella](https://x.com/e_stradella) — 300+ curated resources, deduplicated and distilled into guided workflows that produce real artifacts.

## Prerequisites

This repo is built for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). You need Claude Code installed to use the slash commands.

**Don't have Claude Code?** The `knowledge/` folder contains 19 standalone marketing playbooks you can use with any LLM. Copy them into ChatGPT, Cursor, or any AI tool as context — they work on their own.

## Quick Start

```bash
git clone https://github.com/sderosiaux/marketing-prompts-for-founders.git
cd marketing-prompts-for-founders
```

Open in Claude Code and type:

```
/marketing:journey
```

It asks where you are and tells you exactly what to do next.

## What It Looks Like

```
You: /marketing:journey

Claude: Where are you right now?
  A) I have an idea but haven't validated it yet
  B) I have a product but no landing page
  C) I have a landing page but zero users
  D) I have some users (< 100) but need more
  ...

You: C

Claude: You need users fast. Is your product B2B SaaS, dev tool, or consumer?

You: B2B SaaS

Claude: Run /marketing:outreach — cold outreach gets the fastest feedback at your stage.
        Then /marketing:launch for broader reach.
```

Then `/marketing:outreach` asks about your product and generates 3 cold email templates, a lead sourcing strategy, and a 2-week outreach sequence — all customized to your specific product and audience.

## Commands

### Start here

| Command | What It Does |
|---|---|
| `/marketing:journey` | Diagnoses your stage, tells you what to do next |

### Foundation (do these first)

| Command | What It Does |
|---|---|
| `/marketing:validate` | Test if your idea is worth building — 7-day playbook |
| `/marketing:research` | User interviews, surveys, PMF measurement |
| `/marketing:icp` | Define who you're building for + positioning |
| `/marketing:landing-page` | Generate landing page copy section by section |
| `/marketing:pricing` | Set pricing strategy, tiers, and pricing page copy |

### Getting Users

| Command | What It Does |
|---|---|
| `/marketing:launch` | Plan launch across Product Hunt, HN, directories |
| `/marketing:outreach` | Cold email system — leads, templates, sequences |
| `/marketing:social` | Pick ONE platform, build profile + content plan |
| `/marketing:reddit` | Reddit marketing without getting banned |

### Scaling Growth

| Command | What It Does |
|---|---|
| `/marketing:seo` | Keyword strategy, content plan, page structure |
| `/marketing:llm-seo` | Get recommended by ChatGPT and AI search |
| `/marketing:content` | Content strategy, topics, distribution |
| `/marketing:ads` | Paid ads — platform, budget, campaign structure |
| `/marketing:email` | Onboarding sequences, lifecycle emails, retention |

### Review & Optimize

| Command | What It Does |
|---|---|
| `/marketing:review` | Role-play as your target customer to stress-test any artifact |
| `/marketing:audit` | Audit a live page for SEO, messaging, and conversion issues |
| `/marketing:write` | Write a blog post, Show HN post, Twitter thread, or LinkedIn post |
| `/marketing:cro` | Conversion rate optimization — CTAs, signup flow |

### Advanced Channels

| Command | What It Does |
|---|---|
| `/marketing:influencer` | Find and partner with creators |
| `/marketing:affiliates` | Set up affiliate and referral programs |
| `/marketing:free-tools` | Build free tools that drive traffic |
| `/marketing:growth` | Stage-specific growth tactics and weekly plan |

## How It Works

Each command:
1. **Asks** 3-5 questions about your specific product
2. **Walks** you through the methodology step by step
3. **Generates** customized artifacts (copy, emails, plans, strategies)
4. **Points** you to what to do next

The knowledge base behind the commands contains frameworks, templates, benchmarks, and anti-patterns synthesized from 300+ articles. Claude reads them to inform its advice — you never see raw theory, only customized output.

## Using Without Claude Code

The `knowledge/` folder works standalone. Each file is a complete marketing playbook:

```
knowledge/
├── 01-idea-validation.md        # Hypothesis scoring, 7-day validation playbook
├── 03-icp-positioning.md        # ICP frameworks, positioning templates
├── 04-landing-pages-messaging.md # Page structure, headline formulas
├── 07-seo.md                    # Keyword categories, APTK framework
├── 11-cold-outreach.md          # Email sequences, trigger events
├── ...                          # 19 files total
└── _INDEX.md                    # Quick reference map
```

Copy any file into your LLM of choice and ask it to help you apply the frameworks to your product.

## Credits

- Source material: [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders) by [@e_stradella](https://x.com/e_stradella)
- Key sources: PostHog, Lenny's Newsletter, MR Unlocked, Growth Unhinged, GTM Strategist, MarkePear, and many more (see individual knowledge files for full attribution)

## License

MIT
