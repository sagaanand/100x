# 100x Research Project

## Research Topic: Cold Outreach Pipeline for B2B SaaS

This repository documents deep research into cold outreach best practices for B2B SaaS companies, collected from 10 practitioners who have built and run real outbound machines.

---

## Why Cold Outreach Pipeline

Cold outreach remains the highest-leverage channel for early-stage B2B SaaS. Unlike SEO or community, it produces predictable, repeatable revenue when systemized. It's the only channel where you can go from zero pipeline to qualified meetings in days, not months.

The challenge: the playbook is saturated. What worked in 2018 (Predictable Revenue cadences, spray-and-pray sequences) is now the baseline — buyers have immunity to it. This research captures what's working in 2024–2026, from practitioners who are testing it live.

---

## How Content Was Collected

- **Blogs and long-form content:** Scraped and summarized from expert websites (joshbraun.com, close.com, outboundsquad.com, predictablerevenue.com, jbarrows.com, samnelson.substack.com)
- **Podcast episode summaries:** Sourced from show notes and third-party coverage (Mixmax interviews, Bowery Capital, HubSpot Master in Sales)
- **YouTube video content:** Summarized from video descriptions, third-party write-ups, and framework documentation (YouTube transcript API blocked from cloud environments; documented in transcripts files)
- **LinkedIn posts:** Reconstructed from LinkedIn public posts, referenced articles, and framework documentation

All content is collected from publicly available sources and attributed to original creators.

---

## Repository Structure

```
research/
├── sources.md                          # All 10 experts: profiles, links, annotations
├── linkedin-posts/
│   ├── josh-braun.md                   # 5 posts: 4T Framework, Coffee Test, Be Cheeky
│   ├── jason-bay.md                    # 5 posts: Too Good To Ignore, cold call framework
│   ├── morgan-j-ingram.md              # 5 posts: 10/30/10, video prospecting, LinkedIn DMs
│   ├── ronen-pessar.md                 # 5 posts: cold call openers, 2-phase system, SDR traits
│   ├── john-barrows.md                 # 5 posts: GSF, AI era, empathy in sales
│   ├── steli-efti.md                   # 2 posts: 30 Cold Calling Tips, core philosophy
│   ├── aaron-ross.md                   # 5 posts: SDR model evolution, signal-based outbound
│   ├── nick-cegelski.md                # 5 posts: Reply Method, objection scripts, multi-threading
│   ├── alex-berman.md                  # 5 posts: 3C Framework, personalization math, follow-up
│   └── sam-nelson.md                   # 5 posts: call reluctance, AI in SDR, Nooks analysis
├── youtube-transcripts/
│   ├── josh-braun-4t-framework.md      # "Overcome Prospect Resistance" (April 2024)
│   ├── jason-bay-outbound-sales-pitch.md # "Perfect Outbound Sales Pitch" (Oct 2024)
│   ├── morgan-ingram-video-prospecting.md # "Using Videos For Prospecting" (2024)
│   └── nick-cegelski-cold-calling-sucks.md # "Cold Calling Sucks" book talk (Aug 2024)
└── other/
    ├── framework-synthesis.md          # Cross-expert patterns and comparisons
    └── tech-stack-and-tools.md         # Tools referenced across all experts
```

---

## The 10 Experts (Summary)

| # | Expert | Company | Why Chosen |
|---|---|---|---|
| 1 | **Jason Bay** | Outbound Squad | 20K+ reps trained at Zoom, Gong, Rippling; "Too Good To Ignore" framework; 29–54% pipeline lift in 90 days |
| 2 | **Josh Braun** | Braun Sales Academy | 8K+ members; 4T Framework is the most-referenced cold email system in B2B SaaS; real email teardowns, not theory |
| 3 | **Alex Berman** | Galadon | Sent 1M+ cold emails; personalized email converts at 7–8% vs. 1% for templates; ICP validation via cold email |
| 4 | **Morgan J Ingram** | AMP Creative | 10/30/10 video prospecting formula; 45% response rates; trains Salesforce, Google, Snowflake |
| 5 | **Aaron Ross** | Predictable Revenue Inc. | Created Salesforce's outbound system; author of the canonical SDR playbook; now publicly examining what broke |
| 6 | **Nick Cegelski** | 30 Minutes to President's Club | #1 Sales Podcast (3.6M downloads); Gong data from 300M calls; book sold 100K+ copies |
| 7 | **Ronen Pessar** | RP Advisory | 6x SDR/Sales Leader; 2-phase live pilot system; cold call openers with 20–40% connect rate |
| 8 | **John Barrows** | JB Sales Training | 25+ years training Fortune 500 sales teams; "Give a Shit Factor" (GSF) as the AI-era moat |
| 9 | **Steli Efti** | Close.com | YC alum; built a CRM as a practitioner; "Never stop until YES or NO" philosophy; 30 Cold Calling Tips (2026) |
| 10 | **Sam Nelson** | SDRLeader.com | 6 years at Outreach (top SDR → leader); Agoge Pizza Challenge; building SDR leadership as a profession |

---

## Key Insights from the Research

**1. Personalization beats volume, every time**  
Alex Berman: 7–8% conversion (personalized) vs. 1% (templates). Morgan J Ingram: 45% video response rate vs. 2–5% cold email. The math always favors quality.

**2. Give prospects control to increase response rates**  
Six of ten experts independently arrive at permission-based or low-pressure frameworks. Counterintuitively, making it easier to say no increases yeses.

**3. The SDR role is being compressed by AI**  
AI eliminates administrative work (research, logging, sequencing). What remains — real conversations, signal interpretation, genuine curiosity — is actually higher-skill. The SDR role is upgrading, not dying.

**4. Signal-based outbound is the next evolution**  
Reach out when something changes in the prospect's world (funding, job change, product launch, content published). Calendar-based cadences are dying; trigger-based outreach is the replacement.

**5. Multi-channel is table stakes**  
Email → LinkedIn → Phone → Video. Not email alone. Deals with multiple stakeholders close at 2x the rate of single-threaded outbound (Nick Cegelski, Gong data).

---

## Setup Notes

### Tools Installed
- **Cursor IDE:** Installed for AI-native code editing
- **Claude Code:** Extension (Anthropic) — used for this research collection
- **Codex:** Extension (OpenAI)

### Steps Completed
1. Installed Cursor IDE and registered an account
2. Configured AI extensions (Claude Code and Codex)
3. Created public GitHub repository
4. Cloned repository and initialized project structure
5. Completed cold outreach research collection (10 experts, 4 content directories)

### Known Issues
- Claude Code extension can't log in from IDE due to free subscription limitations
- YouTube transcript API blocked from cloud IPs — video content sourced from third-party documentation
