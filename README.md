<div align="center">

# 🌐 awesome-rss-feeds

> 💎 **3234+ curated, live, HTTP-validated English RSS feeds — the most complete open RSS library**

[![Live feeds](https://img.shields.io/badge/live_feeds-3234+-brightgreen?style=for-the-badge)](LIST.md)
[![English only](https://img.shields.io/badge/English_only-3234-2188FF?style=for-the-badge)](#-quick-start)
[![Categories](https://img.shields.io/badge/categories-16-orange?style=for-the-badge)](#-quick-start)
[![Stars](https://img.shields.io/github/stars/aiworkflowpro/awesome-rss-feeds?style=for-the-badge&logo=github&color=181717)](https://github.com/aiworkflowpro/awesome-rss-feeds/stargazers)

</div>

---

> 🎯 **Algorithms wrap you in a filter bubble, platforms chain you to a timeline, and AI-generated content is destroying the signal-to-noise ratio — RSS is the last pillar for taking back control of what you read.**
>
> The most complete open index of **English** RSS feeds. We aggregate open-source upstream lists → HTTP-validate every feed to drop dead links → organize by topic → keep **3234+ live feeds** across **16 categories**, with AI as a first-class focus.

<div align="center">

[🚀 Quick Start](#-quick-start) · [📚 Full List](LIST.md) · [🤝 Contribute](#-contributing) · [🌐 AI Workflow Pro](https://aiworkflowpro.com)

</div>

---

## 🚀 Quick Start

| What you want to read | Category | Feeds |
|---|---|---:|
| 🧠 AI Research & Labs | [feeds/en-ai-research.opml](feeds/en-ai-research.opml) | **127** |
| 🧩 AI Tools & Agents | [feeds/en-ai-tools.opml](feeds/en-ai-tools.opml) | **107** |
| 🔐 Cybersecurity | [feeds/en-cybersecurity.opml](feeds/en-cybersecurity.opml) | **817** |
| ⚛️ Web Frontend & Standards | [feeds/en-web-frontend.opml](feeds/en-web-frontend.opml) | **735** |
| 🛠️ Developer Tools | [feeds/en-dev-tools.opml](feeds/en-dev-tools.opml) | **262** |
| 💻 Backend & Systems | [feeds/en-backend.opml](feeds/en-backend.opml) | **82** |
| ☁️ DevOps & Data | [feeds/en-devops-data.opml](feeds/en-devops-data.opml) | **23** |
| 📱 Mobile Development | [feeds/en-mobile.opml](feeds/en-mobile.opml) | **70** |
| 🏗️ Engineering Team Blogs | [feeds/en-tech-teams.opml](feeds/en-tech-teams.opml) | **470** |
| 🎨 Product Design & UX | [feeds/en-product-design.opml](feeds/en-product-design.opml) | **62** |
| 🚀 Startups & Indie Hackers | [feeds/en-startups.opml](feeds/en-startups.opml) | **65** |
| 💰 Finance & Investing | [feeds/en-finance.opml](feeds/en-finance.opml) | **37** |
| ✍️ Essays & Ideas | [feeds/en-essays.opml](feeds/en-essays.opml) | **78** |
| 🌿 Life & Culture | [feeds/en-lifestyle.opml](feeds/en-lifestyle.opml) | **208** |
| 🎧 Podcasts & Audio | [feeds/en-podcasts.opml](feeds/en-podcasts.opml) | **80** |
| 📬 Newsletters | [feeds/en-newsletters.opml](feeds/en-newsletters.opml) | **11** |

> 💡 **Import everything at once:** [feeds.opml](feeds.opml) · **Full feed list:** [LIST.md](LIST.md)

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

MIT License © 2026 AI Workflow Pro. Feed data is aggregated from public open-source upstream lists; those lists retain their own licenses.
