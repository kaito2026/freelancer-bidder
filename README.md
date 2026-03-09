# 🎯 Freelancer Auto Bidder

> Automatically scan Freelancer.com for matching projects and draft personalized, winning bid proposals — powered by AI.

[![ClawHub](https://img.shields.io/badge/ClawHub-freelancer--bidder-blue)](https://clawhub.com/skills/freelancer-bidder)
[![License: MIT-0](https://img.shields.io/badge/License-MIT--0-green)](LICENSE)

---

## 🤔 What is this?

Freelancing is a numbers game — but writing the same proposal over and over is exhausting. This skill automates the boring part:

1. **Scans** Freelancer.com for fresh projects matching your skills
2. **Ranks** them by budget, relevance, and recency
3. **Drafts** a personalized bid proposal for each one
4. **Tracks** your bids in a simple log file

You focus on the work. Let AI handle the hustle.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔍 Job Search | Search by skill keywords, budget range, and post time |
| 📝 Bid Drafting | AI-generated proposals tailored to each job |
| 📊 Bid Tracking | Simple `bids.md` log to track win rates |
| 💡 Price Suggestion | Recommends optimal bid amount based on project budget |
| 🌍 Multi-language | Drafts proposals in English, Chinese, Spanish, and more |

---

## 🚀 Quick Start

### 1. Install via ClawHub

```bash
clawhub install freelancer-bidder
```

### 2. Find matching jobs

```
Find Freelancer projects for: Python, web scraping, data analysis
Budget: $50-$300
Posted within: last 24 hours
```

### 3. Draft a bid

```
Draft a bid for this project:
[paste project title and description]

My background: 3 years Python developer, built 20+ scraping tools
Tone: professional but friendly
```

### 4. Track your bids

Your bids get logged automatically in `bids.md`:

```markdown
| Date       | Project                  | Budget | Status  |
|------------|--------------------------|--------|---------|
| 2024-03-09 | Python scraper for leads | $150   | Pending |
| 2024-03-08 | Data pipeline automation | $400   | Won ✅  |
```

---

## 📋 Example Output

**Input:**
```
Find Python scraping jobs under $200, posted today
```

**Output:**
```
Found 6 matching projects:

1. 💰 $80-120 | Scrape product prices from 5 e-commerce sites
   Posted: 2 hours ago | 8 bids | ⭐ Client rating: 4.8

2. 💰 $150-200 | Build LinkedIn data extractor
   Posted: 5 hours ago | 3 bids | ⭐ Client rating: 4.5

3. 💰 $50-80 | Extract table data from 200 PDF files
   Posted: 8 hours ago | 12 bids | ⭐ Client rating: 4.2
...
```

**Draft bid for project #1:**
```
Hi! I noticed you need product prices scraped from 5 e-commerce sites.

I've built 20+ scrapers handling exactly this — including sites with 
anti-bot protection. I can deliver clean CSV/JSON output with automated 
daily updates if needed.

Timeline: 2-3 days
My bid: $95

Quick question: do you need this to run automatically on a schedule, 
or is a one-time export enough?

Looking forward to working together!
```

---

## 💡 Winning Bid Tips

1. **Speed matters** — Bid within the first hour. First 5 bidders get 3× more views.
2. **Be specific** — Reference the client's exact problem, not generic claims.
3. **Keep it short** — Under 150 words for fixed-price projects.
4. **End with a question** — Shows genuine interest, increases reply rate by 40%.
5. **Competitive pricing** — Bid 10-15% below the midpoint on your first few jobs.

---

## 🛠 Requirements

- [OpenClaw](https://openclaw.ai) installed
- Freelancer.com account (for submitting bids)
- No API keys needed for job search

---

## 📁 File Structure

```
freelancer-bidder/
├── SKILL.md       # Core skill instructions for OpenClaw
├── README.md      # This file
└── bids.md        # Auto-generated bid tracking log (created on first use)
```

---

## 🤝 Contributing

Found a bug? Have a better bid template? PRs welcome!

1. Fork this repo
2. Make your changes
3. Submit a pull request

---

## 📄 License

MIT-0 — Free to use, modify, and distribute. No attribution required.

---

*Built with ❤️ for freelancers who'd rather be building than bidding.*
