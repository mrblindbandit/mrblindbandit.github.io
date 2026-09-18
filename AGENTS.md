# AGENTS.md — GitHub Pages static mirror

> **Other AIs:** read [`AI_CHANGELOG.md`](./AI_CHANGELOG.md) first.

## Mission

You may maintain this **static** public mirror of Blindbandit frontend assets. Keep it professional and in sync with `mr-blindbandit-website` `public/` when possible.

**This is NOT production.** Production is **ChatGPT Sites** → https://mrblindbandit.net  
Live Pages URL: https://mrblindbandit.github.io/

## Broad access (you MAY)

- Update static HTML/CSS/JS/assets
- Improve README, `llms.txt`, `robots.txt`, governance, AGENTS/AI_CHANGELOG
- Fix broken links that are static-safe

## Hard rails (you MUST NOT)

1. Never claim Pages runs Clerk/LiveKit/D1 — those need ChatGPT Sites
2. Never commit secrets
3. Prefer syncing from website `public/` over one-off divergent edits
4. Never force-push destructively without need

## Sync

Preferred source of truth: `mrblindbandit/mr-blindbandit-website` → `public/`  
Website workflow `deploy-github-pages.yml` can publish here when `PAGES_DEPLOY_TOKEN` is set.
