<div align="center">

# 🌐 awesome-rss-feeds

> 💎 **1200+ curated, live RSS feeds · LLM-vetted · take back your reading in the algorithm era**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Live feeds](https://img.shields.io/badge/live_feeds-1200+-brightgreen?style=for-the-badge)](LIST.md)
[![English](https://img.shields.io/badge/English-1207-2188FF?style=for-the-badge)](#-english-1207-feeds)
[![Categories](https://img.shields.io/badge/categories-15-orange?style=for-the-badge)](#-quick-start)
[![)](#-quick-start)
[![Stars](https://img.shields.io/github/stars/aiworkflowpro/awesome-rss-feeds?style=for-the-badge&logo=github&color=181717)](https://github.com/aiworkflowpro/awesome-rss-feeds/stargazers)

</div>

---

> 🎯 **Algorithms wrap you in a filter bubble, platforms chain you to a timeline, and AI-generated content is destroying the signal-to-noise ratio — RSS is the last pillar for taking back control of what you read.**
>
> A curated index of open RSS feeds. We aggregate 7 upstream open-source lists → validate over HTTP to drop dead links → re-classify by topic → and keep **1200+ live feeds**, organized along two axes: **language × category**.
>
> Download an OPML file and import it into your reader in one click, or feed it straight to **Claude Code / Codex** to build a daily AI digest, competitor monitor, writing idea bank, or a local RAG knowledge base.

<div align="center">

[🚀 Quick Start](#-quick-start) · [📚 Full List](LIST.md) · [🤝 Contribute](#-contributing) · [🌐 AI Workflow Pro](https://aiworkflowpro.com)

</div>

---

## Contents

- [🤔 Why RSS still matters in the algorithm era](#-why-rss-still-matters-in-the-algorithm-era)
- [🚀 Quick Start](#-quick-start)
  - [🌍 English (1207 feeds)](#-english-1207-feeds)
- [📥 Import OPML into your reader](#-import-opml-into-your-reader)
- [🤖 Using it with Claude Code / Codex](#-using-it-with-claude-code--codex)
- [🛠️ Recommended toolchain](#️-recommended-toolchain)
- [🤝 Contributing](#-contributing)
- [🙏 Acknowledgments](#-acknowledgments)
- [👋 About](#-about)
- [📄 License](#-license)

---

## 🤔 Why RSS still matters in the algorithm era

> 💡 **The core reasons:** ① no algorithmic interference · ② no ads · ③ no platform lock-in · ④ works across every platform and device

In an age of information overload, *finding what's worth reading* has become harder than *being able to read it at all*. Recommendation algorithms trap you in a filter bubble, social media chains you to infinite scroll, and AI-generated content is rapidly degrading the signal-to-noise ratio.

RSS puts you back in control — what you subscribe to and what you read is entirely your decision:

- 🎯 **No algorithmic interference** — feeds are shown in chronological order; you consume on your own terms
- 🚫 **No ads** — a clean content stream, focused reading
- 🔓 **No platform lock-in** — when a platform changes its rules or algorithm, it can't take your feeds with it
- 🌐 **Cross-platform, cross-device** — the same OPML file works in every reader

> 💎 **RSS is the backbone channel for gathering and filtering information.** Pair it with AI coding tools (Claude Code / Codex) and automation platforms (Make / n8n) to summarize, monitor, translate, and surface topics.

What this repository does is index the good feeds in one place and organize them by reader scenario, so you don't have to search all over or start from scratch — **just pick a category, import it into your reader, and build a personal information network in 30 minutes.**

---

## 🚀 Quick Start

> 🎁 **Pick by language first, then by category.** Download an OPML file and import it into your reader in one click.

| What you want to read | Category | Count |
|---|---|---:|

### 🌍 English (1207 feeds)

| What you want to read | Category | Count |
|---|---|---:|
| React / Vue / CSS / browser standards | [⚛️ Web Frontend & Standards](feeds/en-web-frontend.opml) | **300** |
| Life / culture / travel / food / games / science & health | [🌿 Life & Culture](feeds/en-lifestyle.opml) | 185 |
| Developer tools / open source / language ecosystems | [🛠️ Developer Tools](feeds/en-dev-tools.opml) | 86 |
| AI agents / LLM tools / applications | [🧩 AI Tools & Agents](feeds/en-ai-tools.opml) | 81 |
| AI research labs / institution blogs | [🧠 AI Research & Labs](feeds/en-ai-research.opml) | 80 |
| High-quality English podcasts / audio shows | [🎧 Podcasts & Audio](feeds/en-podcasts.opml) | 77 |
| Backend / systems / programming languages | [💻 Backend & Systems](feeds/en-backend.opml) | 63 |
| English essays / ideas / long-form thinking | [✍️ Essays & Ideas](feeds/en-essays.opml) | 59 |
| Indie hackers / one-person companies / startups / Web3 | [🚀 Startups & Indie Hackers](feeds/en-startups.opml) | 58 |
| iOS / Android / Flutter | [📱 Mobile Development](feeds/en-mobile.opml) | 56 |
| Engineering team blogs (Spotify, Stripe, etc.) | [🏗️ Engineering Team Blogs](feeds/en-tech-teams.opml) | 50 |
| Smashing / NN/g / Figma and visual design | [🎨 Product Design & UX](feeds/en-product-design.opml) | 49 |
| Personal finance / investing / macroeconomics | [💰 Finance & Investing](feeds/en-finance.opml) | 36 |
| Kubernetes / SRE / data engineering / databases | [☁️ DevOps & Data](feeds/en-devops-data.opml) | 20 |
| Newsletters / weeklies / curated picks | [📬 Newsletters](feeds/en-newsletters.opml) | 7 |

> 💡 **Import everything at once:** [feeds.opml](feeds.opml) · **Full feed list:** [LIST.md](LIST.md)

---

## 📥 Import OPML into your reader

After downloading an OPML file, import it according to the reader you use:

| Reader | Import path |
|---|---|
| **Inoreader** | Settings → Import / Export → Import OPML |
| **Feedly** | Settings → Import OPML |
| **NetNewsWire** | File → Import Subscriptions |
| **Miniflux** (self-hosted) | Settings → Import → OPML file |
| **FreshRSS** (self-hosted) | Configuration → Import / Export → Import OPML |
| **Readwise Reader** | Settings → Import → OPML |

> 🎯 **Advice for your first import:**
>
> 1. Don't start with the full `feeds.opml` — 1200+ feeds at once can bog a reader down
> 2. Pick 1–2 category OPMLs that match your interests
> 3. Read for a week, prune what you don't care about, then import the next category

---

## 🤖 Using it with Claude Code / Codex

> 🚀 **RSS is the best information input for AI coding tools.** Claude Code / Codex can run Python directly — hand them an OPML file from this repo and a couple of sentences, and you have an information pipeline with **zero deployment, zero accounts, and zero API keys.**

### 🌅 Scenario 1: Daily AI digest (zero deployment)

Just tell Claude Code or Codex to fetch an OPML from GitHub, parse it with feedparser, and summarize with AI:

```text
You (to Claude Code or Codex):

  Download https://raw.githubusercontent.com/aiworkflowpro/awesome-rss-feeds/main/feeds/en-ai-research.opml,
  parse every feed in it with feedparser, fetch the article bodies from the last 24 hours,
  write a 500-word digest grouped by topic (research / tools / industry / opinion),
  and save it to my local notes folder.
```

🌅 **Wake up to a digest of your own field every morning. No middle service required.**

### 📊 Scenario 2: Competitor / industry monitoring (scheduled job + push)

Ask Codex to write a standalone Python script and register a scheduled job:

```text
You (to Codex):

  Write a Python script: fetch every feed in feeds/en-startups.opml,
  save the current article IDs for de-duplication. On the next run, find the new articles,
  filter by keywords ("launch / pricing change / funding / acquisition"),
  and push the matches (summary + original link) to my local notes.

  Then register a cron job to run it every day at 8am.
```

⏰ **Save two hours a month of manually watching competitors.**

### 📝 Scenario 3: Writing idea bank

```text
You (to Claude Code or Codex):

  From the last week of articles in feeds/en-essays.opml + feeds/en-podcasts.opml,
  use AI to extract trending topics, sort them by frequency, and write them to my notes.
  For each topic include: number of related articles, 3 representative headlines, and the date first seen.
```

✍️ **Open your notes and you have a shortlist of trending topics for your blog, newsletter, or videos.**

### 🌐 Scenario 4: Translate feeds across languages

Great content in one language + AI translation = a personal, translated edition:

```text
You (to Claude Code or Codex):

  Fetch this week's articles from feeds/en-ai-research.opml + feeds/en-web-frontend.opml,
  translate them into concise summaries in my language (keeping technical terms in the original),
  write a weekly report, and archive it to my notes.
```

🌍 **The latest from other language communities, summarized in yours.**

### 🧠 Scenario 5: Local RAG knowledge base

Vectorize all your RSS article content to build your own domain Q&A:

```text
You (to Claude Code or Codex):

  Continuously fetch full text from feeds/en-ai-research.opml + feeds/en-ai-tools.opml,
  feed it into a local ChromaDB / pgvector store, and build a vector index.
  When I ask "what's new in RAG lately", retrieve and answer with AI.
```

🧠 **Turn RSS into a private knowledge base — more precise than a web search, because you curated the sources.**

---

## 🛠️ Recommended toolchain

> Progressively more complex — pick what you need:

| Tier | Tools | Who it's for |
|---|---|---|
| 🟢 **Starter** (zero deployment) | **Claude Code / Codex + Python `feedparser`** | Most people — fetch this repo's OPML directly, one sentence and you're done |
| 🟡 **Automated** (scheduled) | + **cron / launchd** or **n8n / Make** | You want the RSS→AI pipeline to run automatically every day |
| 🟠 **Advanced** (state + multi-device) | + self-hosted **Miniflux / FreshRSS** + REST API | You want read/unread state and incremental updates, synced across devices |
| 🔴 **Pro** (vector index + RAG) | + **ChromaDB / pgvector / Qdrant** | Turn RSS into a queryable knowledge base |
| ✨ **Bonus** (turn any site into RSS) | **RSSHub / RSS-Bridge** | Subscribe to sites without native RSS (social feeds, etc.) |
| 📦 **Output & archive** | **Notion / Obsidian / Logseq** | Long-term storage + cross-device access |

> 💡 **You don't need to deploy Miniflux right away** — for most use cases, **Claude Code / Codex + feedparser + this repo's OPML** is enough. Upgrade only when you actually need to manage hundreds of feeds with synced state across devices.

---

## 🤝 Contributing

Open an [issue](https://github.com/aiworkflowpro/awesome-rss-feeds/issues) to submit:

- 🆕 **Suggest a new feed** — RSS URL + site homepage + suggested category + a short reason
- 💀 **Report a dead link** — provide the broken URL
- 🆕 **Propose a new category** — a brief rationale + the number of feeds that could fill it

See [CONTRIBUTING.md](CONTRIBUTING.md) for the full workflow and inclusion criteria.

---

## 🙏 Acknowledgments

> This repository stands on the shoulders of the open-source projects below. Each upstream list is the real data contributor; this repo does the work of aggregating, unifying the index, reorganizing by reader scenario, HTTP validation, and LLM-based tagging and curation.

| Upstream repo | Link |
|---|---|
| simevidas/web-dev-feeds | [🔗 GitHub](https://github.com/simevidas/web-dev-feeds) |
| impressivewebs/frontend-feeds | [🔗 GitHub](https://github.com/impressivewebs/frontend-feeds) |
| tuan3w/awesome-tech-rss | [🔗 GitHub](https://github.com/tuan3w/awesome-tech-rss) |
| RSS-Renaissance/awesome-blogCN-feeds | [🔗 GitHub](https://github.com/RSS-Renaissance/awesome-blogCN-feeds) |
| plenaryapp/awesome-rss-feeds | [🔗 GitHub](https://github.com/plenaryapp/awesome-rss-feeds) |
| vishalshar/awesome_ML_AI_RSS_feed | [🔗 GitHub](https://github.com/vishalshar/awesome_ML_AI_RSS_feed) |
| foorilla/allainews_sources | [🔗 GitHub](https://github.com/foorilla/allainews_sources) |

If your project's data is used here but isn't listed, open an issue and we'll add it right away.

---

## 👋 About AI Workflow Pro

> 🚀 **AI Workflow Pro** is a one-person product studio building and open-sourcing practical AI workflows — turning AI tools into systems that keep running.

We focus on how AI coding tools (Claude Code / Codex), agents, and automation actually help people ship real work, and we publish hands-on workflows, guides, and field notes on AI coding, agents, RSS automation, and running a one-person company.

| Channel | Link |
|---|---|
| 🌐 **Website** | [aiworkflowpro.com](https://aiworkflowpro.com) |
| 💻 **GitHub** | [@aiworkflowpro](https://github.com/aiworkflowpro) |
| 𝕏 **X / Twitter** | [@aiworkflowprolk](https://x.com/aiworkflowprolk) |

---

## 📄 License

Licensed under the [MIT License](LICENSE) — © 2026 AI Workflow Pro.

The feed data is aggregated from public, open-source upstream lists (see [Acknowledgments](#-acknowledgments)); those lists retain their own licenses.

<div align="center">

### ⭐ If this repo is useful to you, leave a Star

[![Website](https://img.shields.io/badge/🌐_Website-aiworkflowpro.com-FF6B35?style=for-the-badge)](https://aiworkflowpro.com)
[![X / Twitter](https://img.shields.io/badge/𝕏_Twitter-@aiworkflowprolk-000000?style=for-the-badge)](https://x.com/aiworkflowprolk)
[![GitHub](https://img.shields.io/badge/💻_GitHub-aiworkflowpro-181717?style=for-the-badge)](https://github.com/aiworkflowpro)

> 🎯 **Tools change, workflows don't.**

</div>
