# AGENTS.md — mrblindbandit.github.io

Instructions for coding agents working in this **GitHub Pages** static site repository.

## What this repo is

Public **static** deploy of Blindbandit Records HTML/CSS/JS assets, typically synced from `public/` in `mrblindbandit/mr-blindbandit-website`.

Live Pages URL: **https://mrblindbandit.github.io/**

## Production host (critical)

**Real production** (Clerk, LiveKit, D1, Worker/API, secrets) runs on **ChatGPT Sites (OpenAI Sites)** → **https://mrblindbandit.net**.

This Pages repo is a **static mirror only**. Do **not** describe Pages as the product host, and do **not** describe production as “hosted on Cloudflare” as the product host.

Auth callbacks, `/api/`, and dynamic Worker routes do **not** run on GitHub Pages.

## Related repos

| Repo | Role |
|---|---|
| `mrblindbandit/mrblindbandit.github.io` | This static Pages site |
| `mrblindbandit/mr-blindbandit-website` | Canonical source + Worker/API + D1 |
| `mrblindbandit/mr-blindbandit-mobile` | iOS + Android apps |
| `mrblindbandit/mrblindbandit` | GitHub profile README |

## Auth & integrations (on production only)

- **Clerk**: email + Google; Apple off — configured on ChatGPT Sites, not Pages
- **LiveKit**, push, D1 migrations **0007/0008** — website/Worker on Sites
- Prefer editing product logic in `mr-blindbandit-website`, then re-sync static assets here

## Hard rules

1. Never commit secrets
2. Do not wipe legal / privacy / trust-safety pages
3. Keep `robots.txt` and `llms.txt` accurate (production sitemap on mrblindbandit.net)
4. Prefer updating `AI_CHANGELOG.md` for substantial AI-assisted changes
5. Additive content only when mirroring — avoid destructive mass deletes of legal pages

## Read next

- `README.md` — mirror vs production clarification
- `llms.txt` — short site summary for AI crawlers
- `robots.txt` — crawl rules
- Website repo `AGENTS.md` / `docs/ARCHITECTURE.md` for full architecture

## Contact

business@mrblindbandit.net
