# Contributing to awesome-rss-feeds

Thanks for wanting to contribute. Before you open an issue or PR, here's how this repo works.

## We don't accept PRs that edit the OPML files

**The OPML files and `LIST.md` are generated artifacts**, produced by an internal pipeline that is re-run monthly. A PR that edits these files directly would be overwritten on the next run.

If you want to add a feed, report a dead link, or suggest a category, please use the **issue workflow**.

## Issue workflow

### 1. Suggest a new feed

Template: [new-source.yml](.github/ISSUE_TEMPLATE/new-source.yml)

Four fields:
- **RSS feed URL** (required) — must be a valid RSS / Atom feed URL
- **Site homepage URL** — the site the feed belongs to
- **Suggested category** — pick one of seven: ai-and-ml / tech-and-startups / chinese-blogs / dev-and-opensource / design-and-product / news-and-finance / rss-tools
- **Short reason** — why it's worth including (≤200 chars)

### 2. Report a dead link

Template: [dead-link.yml](.github/ISSUE_TEMPLATE/dead-link.yml)

Two fields:
- **Dead URL**
- **Error type** (404 / timeout / content changed / domain gone)

### 3. Propose a new category

Template: [category-suggest.yml](.github/ISSUE_TEMPLATE/category-suggest.yml)

We're deliberately conservative about adding top-level categories — the current seven balance coverage and clarity. A new category must satisfy: **at least 30 feeds could fill it + a clear boundary against the existing seven**.

## Our inclusion process

Around the 1st of each month, maintainers run a monthly audit:

1. Review all issues from the past month
2. Re-crawl all upstream sources
3. Add community-suggested feeds to `manual-add.opml` for inclusion
4. `validate` — three validation gates
5. `categorize` — classify (with human review)
6. `audit` — handle dead links
7. `diff` — generate the CHANGELOG
8. `publish` — push

So a feed you suggest won't be included immediately — expect a 1–30 day delay. Please be patient.

## Decision principles

| Dimension | Standard |
|---|---|
| Inclusion priority | open-source / free > paid |
| Content quality | updated at least weekly + at least 50% full-text RSS (summary-only feeds are marked but not prioritized) |
| Diversity | at most 1–2 feeds per author / outlet (avoid one source dominating a category) |
| Neutrality | extreme-position content is not included |
| Deduplication | not re-included when it duplicates an upstream list (e.g. awesome-blogCN-feeds, awesome-tech-rss) |

## License

By submitting, you agree that your contribution is released under this repository's [MIT License](LICENSE).
