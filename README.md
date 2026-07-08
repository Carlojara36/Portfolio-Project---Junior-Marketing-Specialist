# Portfolio Project Setup - Junior-Marketing-Specialist

## Overview
This repository was created as part of a portfolio project for 100Hires. The goal of this setup was to install the required tools, connect the project to GitHub, and document the process clearly.

## Tools Installed
- Cursor IDE
- Claude Code extension in Cursor
- Codex add-on in Cursor

## Steps Completed
1. Installed Cursor IDE.
2. Opened GitHub in the browser and created a public GitHub repository.
3. Opened a new project in Cursor.
4. Located the Extensions panel using `Cmd + Shift + X`.
5. Installed the Claude Code extension in Cursor and opened it via the sidebar.
6. Installed the Codex add-on in Cursor and opened it via the sidebar. 
7. Logged in to Codex successfully.
8. Initialized the local repository through Cursor's terminal.
9. Connected the local repository to GitHub using the `git remote add` command.
10. Created this `README.md` file.
11. Committed the changes locally.
12. Pushed the repository to GitHub.

## Issues Encountered and How I Resolved Them
- I initially had trouble finding the Extensions panel in Cursor.
- I resolved this by opening a new project and using the `Cmd + Shift + X` shortcut.
- I was able to install Claude Code, but I could not complete login because I did not yet have a Claude Pro or Max account available for sign-in.

---

# LinkedIn Organic Content Strategy for B2B SaaS — Expert Research

## Project Goal

A curated research project compiling actionable frameworks, tactics, and strategies from 10 LinkedIn experts who have demonstrably generated revenue through LinkedIn organic content. Built for B2B SaaS founders and marketers who want to turn LinkedIn into a pipeline channel.

## Expert Selection Criteria

Each expert was selected based on three filters:

1. **Demonstrable revenue/pipeline attribution to LinkedIn** — they show their numbers, not just their follower count
2. **Published, repeatable frameworks** — not just opinions, but systems others can implement
3. **Active in 2025–2026** — LinkedIn's algorithm changed significantly; older advice can hurt reach

## The 10 Experts

| # | Expert | Why Selected | Core Framework |
|---|--------|-------------|----------------|
| 1 | **Justin Welsh** | Built $7.9M solo business via LinkedIn content OS | The Content Operating System — 3-step funnel (Attract → Nurture → Convert) |
| 2 | **Alex Boyd** | Generated $4.5M in revenue from LinkedIn (34% of agency revenue) | LinkedIn as infrastructure, not media — participation > publishing |
| 3 | **Richard van der Blom** | Runs the definitive annual LinkedIn algorithm study | Data-driven posting playbook based on the yearly algorithm change report |
| 4 | **Brendan Hufford** | Correlated LinkedIn impressions to pipeline for B2B SaaS | Content IP framework — name the problem before naming the solution |
| 5 | **Kieran Drew** | Built audience of 400K+ and high-ticket writing business | Writer's audience-building framework — value-first, sell second |
| 6 | **Adam Robinson** | Bootstrapped RB2B to $5M ARR in 13 months with 5 people; attributes 99% of signups to LinkedIn | Build-in-public (monthly P&L), 90/10 content-to-CTA ratio, audience-before-product order of ops |
| 7 | **Chris Walker** | Built Refine Labs to $20M+ ARR using LinkedIn demand gen; created HIRO pipeline metric | Demand Creation vs Demand Capture, HIRO Pipeline, dark social attribution, zero-click content |
| 8 | **Melanie Goodman** | LinkedIn consultant for senior leaders; survived 12-week ban and rebuilt | Reach → Rapport → Results content triage; LinkedIn + Substack flywheel |
| 9 | **Anthony Blatner** | LinkedIn Learning instructor; LinkedIn Ads expert | Thought Leader Ads strategy — amplify people, not company pages |
| 10 | **Dave Gerhardt** | Built Exit Five to $3M+ revenue (5,700+ paid members) driven ~60% by LinkedIn | Omnipresence (multi-account team posting), curate-don't-create, LinkedIn-as-PR-channel |

## Repository Structure

```
research/
  sources.md                  — Full sources, links, and annotations for all 10 experts
  linkedin-posts/             — 10 files, 5-7 posts per expert with verified dates
    justin-welsh.md
    alex-boyd.md
    richard-van-der-blom.md
    brendan-hufford.md
    kieran-drew.md
    adam-robinson.md
    chris-walker.md
    melanie-goodman.md
    anthony-blatner.md
    dave-gerhardt.md
  youtube-transcripts/        — Full transcripts from key YouTube appearances
    justin-welsh-3-step-linkedin-system.md
    justin-welsh-content-os-system.md
    alex-boyd-2025-linkedin-strategy-toolkit.md
    richard-van-der-blom-2025-algorithm.md
    brendan-hufford-whats-killing-your-content.md
    kieran-drew-500k-writing.md
    kieran-drew-million-dollar-writing.md
    anthony-blatner-linkedin-ads-strategy.md
    melanie-goodman-platform-ban-to-substack.md
    adam-robinson-linkedin-social-selling.md
    adam-robinson-safe-doesnt-scale.md
    chris-walker-dark-social.md
    chris-walker-state-of-b2b-marketing.md
    chris-walker-revenue-vitals-live.md
    dave-gerhardt-master-linkedin-b2b.md
    dave-gerhardt-lifecycle-marketing.md
  other/                      — Podcast episodes, articles, and newsletters by expert
    justin-welsh.md
    alex-boyd.md
    richard-van-der-blom.md
    brendan-hufford.md
    kieran-drew.md
    adam-robinson.md
    chris-walker.md
    melanie-goodman.md
    anthony-blatner.md
    dave-gerhardt.md
```

## Key Cross-Expert Themes

1. **Topic Authority > Follower Count** — LinkedIn's 2025-2026 algorithm (360Brew / Interest Graph) rewards depth and consistency on a specific topic, not network size.
2. **Personal Profiles > Company Pages** — Every expert emphasizes posting from personal profiles. Company pages reach ~1.6% of followers organically.
3. **Carousels/Documents Win** — Highest dwell time and algorithmic preference; lowest competition (<5% of posts use them).
4. **The Link Tradeoff** — External links can reduce reach when dropped thoughtlessly, but high-value linked content performs well. Context matters more than the link itself.
5. **2-4 Posts/Week Optimal** — Daily posting causes content fatigue and -45% reach over time.
6. **Commenting Is Compounding** — Several experts treat commenting as a primary growth lever, not a side activity.
7. **Founder-Led > Brand-Led** — Buyers evaluate trust in people before products. The companies generating the most LinkedIn pipeline have founders posting consistently.

## Data Sources

- LinkedIn post IDs (cross-referenced where possible)
- Expert Substack/newsletter archives
- Podcast transcripts (YouTube, Buzzsprout, Podbean)
- Published algorithm reports (van der Blom, Saywhat Q1 2026)
- Expert websites and LinkedIn Learning courses

## Tools Used

- `youtube-transcript` npm package for YouTube transcript extraction
- Git + GitHub for version control
- Claude Code (via Cursor IDE)

---

*Research compiled July 2026. LinkedIn's algorithm changes frequently — timestamps on all posts and transcripts are verified.*
