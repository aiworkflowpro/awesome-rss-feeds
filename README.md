<div align="center">

# 🌐 awesome-rss-feeds

> 💎 **8936+ curated, live, HTTP-validated English RSS feeds — the most complete open RSS library**

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat)](LICENSE)
[![Live feeds](https://img.shields.io/badge/Live_feeds-8936+-10B981?style=flat)](LIST.md)
[![Categories](https://img.shields.io/badge/Categories-21-blue?style=flat)](#-quick-start)

[🚀 Quick Start](#-quick-start) · [📚 Full List](LIST.md) · [🤝 Contribute](#-contributing) · [🌐 AI Workflow Pro](https://aiworkflowpro.com)

</div>

---

> 🎯 **Algorithms wrap you in a filter bubble, platforms chain you to a timeline, and AI-generated content is destroying the signal-to-noise ratio — RSS is the last pillar for taking back control of what you read.**
>
> The most complete open index of **English** RSS feeds. We aggregate open-source upstream lists → HTTP-validate every feed to drop dead links → organize by topic → keep **8936+ live feeds** across **21 categories**, with AI as a first-class focus.

---

## Why This List

Most RSS collections are one-time link dumps that rot as feeds go dark. This one is maintained:

- **HTTP-validated** — every feed returns a live status and at least one parseable item before it lands here, and is re-checked periodically
- **English-only, topic-classified** — feeds are sorted by their *actual content*, not just their upstream source, so each category stays on-topic
- **AI as a first-class focus** — split into Research & Labs, Engineering & LLM, and News & Insights instead of buried in a generic "tech" bucket
- **Source-preserved** — every upstream list is credited, and the full validation funnel is published in [stats.json](stats.json)

> [!TIP]
> Import [feeds.opml](feeds.opml) to grab all 8936+ feeds at once, or pick a single category below.

---

## 🚀 Quick Start

| What you want to read | Category | Feeds |
|---|---|---:|
| 🧠 AI Research & Labs | [feeds/en-ai-research.opml](feeds/en-ai-research.opml) | **121** |
| ⚙️ AI Engineering & LLM | [feeds/en-ai-eng.opml](feeds/en-ai-eng.opml) | **230** |
| 📡 AI News & Insights | [feeds/en-ai-news.opml](feeds/en-ai-news.opml) | **93** |
| 🔐 Cybersecurity | [feeds/en-cybersecurity.opml](feeds/en-cybersecurity.opml) | **550** |
| ⚛️ Web Frontend & Standards | [feeds/en-web-frontend.opml](feeds/en-web-frontend.opml) | **1035** |
| 🛠️ Developer Tools | [feeds/en-dev-tools.opml](feeds/en-dev-tools.opml) | **101** |
| 💻 Backend & Systems | [feeds/en-backend.opml](feeds/en-backend.opml) | **172** |
| ☁️ DevOps & Data | [feeds/en-devops-data.opml](feeds/en-devops-data.opml) | **45** |
| 📱 Mobile Development | [feeds/en-mobile.opml](feeds/en-mobile.opml) | **69** |
| 🏗️ Engineering Team Blogs | [feeds/en-tech-teams.opml](feeds/en-tech-teams.opml) | **169** |
| 🎨 Product Design & UX | [feeds/en-product-design.opml](feeds/en-product-design.opml) | **27** |
| 🔬 Science | [feeds/en-science.opml](feeds/en-science.opml) | **368** |
| 🚀 Startups & Indie Hackers | [feeds/en-startups.opml](feeds/en-startups.opml) | **94** |
| 💰 Finance & Investing | [feeds/en-finance.opml](feeds/en-finance.opml) | **207** |
| 📰 News & Politics | [feeds/en-news.opml](feeds/en-news.opml) | **1225** |
| ✍️ Essays & Ideas | [feeds/en-essays.opml](feeds/en-essays.opml) | **1616** |
| 🎬 Entertainment | [feeds/en-entertainment.opml](feeds/en-entertainment.opml) | **942** |
| 🏆 Sports | [feeds/en-sports.opml](feeds/en-sports.opml) | **404** |
| 🌿 Life & Culture | [feeds/en-lifestyle.opml](feeds/en-lifestyle.opml) | **1166** |
| 🎧 Podcasts & Audio | [feeds/en-podcasts.opml](feeds/en-podcasts.opml) | **245** |
| 📬 Newsletters | [feeds/en-newsletters.opml](feeds/en-newsletters.opml) | **57** |

> 💡 **Import everything at once:** [feeds.opml](feeds.opml) · **Full feed list:** [LIST.md](LIST.md)
>
> 🎯 **Quality over quantity.** Every feed is HTTP-validated and classified by its *actual content* (article titles + upstream source). No-topic noise — random local rags, dead personal blogs, niche hobbies — is filtered out. **AI is a first-class focus**, split into Research & Labs, Engineering & LLM, and News & Insights.

---

## 📥 Import OPML into your reader

| Reader | Import path |
|---|---|
| **Inoreader** | Settings → Import / Export → Import OPML |
| **Feedly** | Settings → Import OPML |
| **NetNewsWire** | File → Import Subscriptions |
| **Miniflux** / **FreshRSS** (self-hosted) | Settings → Import → OPML |
| **Readwise Reader** | Settings → Import → OPML |

---

## 🤖 Using it with Claude Code / Codex

Hand an OPML file from this repo to Claude Code or Codex and a couple of sentences, and you have an information pipeline with zero deployment:

```text
Download https://raw.githubusercontent.com/aiworkflowpro/awesome-rss-feeds/main/feeds/en-ai-research.opml,
parse every feed with feedparser, fetch the article bodies from the last 24 hours,
and write a 500-word digest grouped by topic to my notes.
```

---

## ✅ Why every feed works

Every feed is validated over HTTP (status 200 + a feed content-type + at least one parseable item) before it lands here, and re-checked periodically. Dead links are dropped. The validation funnel is published in [stats.json](stats.json).

---

## 🤝 Contributing

Open an [issue](https://github.com/aiworkflowpro/awesome-rss-feeds/issues) to suggest a new feed, report a dead link, or propose a category. See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 🙏 Acknowledgments

This repository aggregates and re-indexes the public, open-source upstream lists below. Each upstream is the real data contributor; this repo validates, dedupes, and reorganizes by topic.

- plenaryapp/awesome-rss-feeds · simevidas/web-dev-feeds · impressivewebs/frontend-feeds
- tuan3w/awesome-tech-rss · RSS-Renaissance/awesome-AI-feeds · RSS-Renaissance/awesome-blogCN-feeds
- vishalshar/awesome_ML_AI_RSS_feed · foorilla/allainews_sources
- **alan-turing-institute/ai-rss-feeds** (self-generated feeds for AI sites without RSS)
- **leontloveless/ai-rss-feeds** · jonchretien/dev-lists · JackyST0/awesome-rsshub-routes · chrbailey/agent-data-sources

---

## 👋 About AI Workflow Pro

[🌐 aiworkflowpro.com](https://aiworkflowpro.com) · [𝕏 @aiworkflowprolk](https://x.com/aiworkflowprolk) · [💻 GitHub](https://github.com/aiworkflowpro)

## 📄 License

CC0-1.0 — dedicated to the public domain, see [LICENSE](LICENSE). Feed data is aggregated from public open-source upstream lists; those lists retain their own licenses.

---

## More from AI Workflow Pro

| Project | What it is |
|---|---|
| **[awesome-rss-feeds-list](https://github.com/aiworkflowpro/awesome-rss-feeds-list)** | **8936+ curated English RSS feeds across 21 categories** |
| [awesome-ai-practices-list](https://github.com/aiworkflowpro/awesome-ai-practices-list) | AI best practices, auto-curated every 6h by DigestOps |
| [awp-workflow-agent-spec](https://github.com/aiworkflowpro/awp-workflow-agent-spec) | Specification for production-grade Claude Code Skills |
| [awp-video-editing-skill](https://github.com/aiworkflowpro/awp-video-editing-skill) | Claude Code Skill for automated video editing |

🌐 [aiworkflowpro.com](https://aiworkflowpro.com) · 👤 [@aiworkflowpro](https://github.com/aiworkflowpro)

---

<div align="center">

### If this list saves you time, a ⭐ helps others find it

[![Website](https://img.shields.io/badge/🌐_Website-aiworkflowpro.com-10B981?style=flat)](https://aiworkflowpro.com)
[![X](https://img.shields.io/badge/𝕏-@aiworkflowprolk-000000?style=flat)](https://x.com/aiworkflowprolk)

**Building AI tools in public — the products, the process, the lessons.**

</div>
