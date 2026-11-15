---
tags:
  - knowledge-management
  - systems-thinking
  - information-systems
  - workflow
---

# Synthesising AI Research into a Digital Garden

*Synthesised from the initial design conversation that created this Digital Garden (November 2026).*

## The Problem: Ephemeral Chat Context

When reading books (such as a one-month library loan of *Sapiens*) or exploring technical topics with AI assistants, valuable insights and syntheses emerge during conversation. However, chat histories are chronological and ephemeral: once the interaction finishes or the book is returned, those structured takeaways are hard to locate, cross-reference, or browse.

## Design Goals

1. **Durable Static Content:** Store finalised notes as plain Markdown files in Git so they remain portable and version-controlled.
2. **Dual Organisation (Source + Theme):**
   - Keep chapter-by-chapter notes tied to a specific book (`docs/books/`).
   - Extract evergreen, cross-cutting concepts into standalone thematic articles (`docs/topics/`) and link them via tags (`docs/tags.md`).
3. **Zero-Maintenance Publishing:** Automatically build and publish a searchable static web frontend on every push to `main`.

## Architecture & Tooling Decisions

### 1. Static Frontend Comparison

| Option | Strengths | Trade-offs | Verdict |
| :--- | :--- | :--- | :--- |
| **MkDocs Material** | Purpose-built for hierarchical chapters and topics; instant client-side search; built-in tags index; zero JS frontend maintenance. | Less native graph visualisation than Quartz. | **Selected** |
| **Quartz (v4)** | Obsidian-style backlinks and interactive graph view. | Better suited to unstructured wiki vaults than structured book chapters. | Alternative |
| **Astro Starlight** | Full component customisation and MDX support. | Higher Node/frontend tooling overhead for pure text notes. | Overkill |

### 2. Hosting Comparison (GitHub Pages vs. Vercel Hobby)

- **GitHub Pages (via GitHub Actions):**
  - *Pros:* Native `mkdocs gh-deploy` support in Python; single platform for Markdown source, build pipeline, and hosting; no third-party build container quirks.
  - *Catch:* Free GitHub accounts only support GitHub Pages on **public** repositories (private repositories require GitHub Pro).
- **Vercel (Hobby Plan):**
  - *Pros:* Deploys from **private** GitHub repositories for free; automatic preview URLs on pull requests.
  - *Catch:* Node-centric build image requires explicit Python dependency steps (`vercel.json`).
- **Decision:** Made the `digital-garden` repository public and deployed via GitHub Actions to **GitHub Pages**, while retaining `vercel.json` in the repo for portability.

## Ongoing Workflow

1. **Explore & Discuss:** Read a chapter or research a topic in an AI chat session.
2. **Synthesise:** Distil the conversation into structured Markdown bullet points, callout admonitions, and comparison tables.
3. **Classify:**
   - Add source-specific notes under `docs/books/<book-name>/`.
   - Extract broader mental models into `docs/topics/<topic-name>.md`.
   - Add frontmatter `tags` and register new pages in `mkdocs.yml`.
4. **Publish:** Commit and push to `main`; GitHub Actions automatically rebuilds and updates the live site.
