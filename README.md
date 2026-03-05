# Sapinover Overnight Data

Research library and analytical data supporting Sapinover LLC's overnight ATS market microstructure work.

## What This Repo Contains

### Market Research

| File | Description |
|------|-------------|
| `Korean_Retail_Overnight_Trading_US_Market_Access.md` | Comprehensive analysis of Korean retail investor demand for overnight U.S. equity access — $163.6B in holdings, ETF power-user behavior, regulatory timeline, and implications for overnight ATS volume patterns. Based on [Bruce Markets research](https://www.brucemarkets.com/korean-retail-market-snapshot-the-state-of-us-market-access/) (Feb 2026). |

### Dashboard Data (`dashboard_data/`)

Pre-computed JSON datasets powering the [Sapinover Overnight ATS Dashboard](https://ejcacciatore.github.io/Sapinover_Overnight_Data/):

| File | Contents |
|------|----------|
| `summary_stats.json` | Aggregate statistics across the full sample period |
| `daily_volume.json` | Per-session volume and notional breakdowns |
| `alpha_metrics.json` | Timing differential and captured alpha analysis |
| `beta_distribution.json` | Distribution of overnight beta values |
| `directional_success.json` | Directional consistency rates by segment |
| `etf_analysis.json` | ETF-specific overnight trading patterns |
| `mcap_analysis.json` | Market capitalization tier analysis |
| `sector_breakdown.json` | Sector-level composition and metrics |
| `spread_analysis.json` | Bid-ask spread characteristics during overnight hours |
| `top_symbols.json` | Most active symbols by volume and notional |

### Dashboard

| File | Description |
|------|-------------|
| `Sapinover_Overnight_ATS_Dashboard.html` | Static HTML dashboard for visualizing overnight ATS volume data |

## Related Repositories

| Repo | Purpose |
|------|---------|
| [sapinover-overnight-dashboard](https://github.com/ejcacciatore/sapinover-overnight-dashboard) | Primary research dashboard — 84 trading days, 60,955+ observations, password-protected, AES-256-GCM encrypted |
| [Sapinover-Overnight-Lunar](https://github.com/ejcacciatore/Sapinover-Overnight-Lunar) | Lunar New Year 2026 event study — on/off/on volume pattern during Asian market closures |
| [sapinover-overnight-alpha](https://github.com/ejcacciatore/sapinover-overnight-alpha) | U.S. equity trading venue database with interactive interface |
| [sapinover-project](https://github.com/ejcacciatore/sapinover-project) | Main Sapinover platform (Next.js 14 on Vercel) — embeds dashboard content |

## Context

This repository serves as the research and intelligence arm of Sapinover's overnight trading analysis. While the primary dashboard repo contains the interactive visualization and encrypted institutional data, this repo houses the contextual analysis, global demand research, and supporting datasets that give the quantitative work its real-world grounding.

The Korean retail market research is the first installment in a planned series examining how international retail demand is reshaping expectations for U.S. overnight market access.

---

Sapinover LLC · [sapinover-project.vercel.app](https://sapinover-project.vercel.app) · Forward Thinking, Transparent Actions
