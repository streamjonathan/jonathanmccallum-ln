# AGENTS.md — jonathanmccallum-ln (Lingala mirror of jonathanmccallum.com)

Lingala mirror site. Same theme and design as the main site (Paper Light),
content translated into Lingala, meaning-first. Repo: streamjonathan/jonathanmccallum-ln.
Live: jonathanmccallum-ln.pages.dev (Jonathan approved all 50 mirrors live, 22 Nov 2026).
Custom subdomain ln.jonathanmccallum.com comes later, via the dashboard.

## Mission

Mirror jonathanmccallum.com in Lingala — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## Publishing

Jonathan approved all 50 language mirrors live (22 Nov 2026), so this mirror
goes live on jonathanmccallum-ln.pages.dev with its 5 proof articles.
The custom subdomain ln.jonathanmccallum.com is a later dashboard step. New articles stay drafts
until he approves them.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: direct address "yo" (singular, warm, direct) throughout — same
  choice as the French proof's "tu". FLAG for Jonathan: respectful "bino"
  would change every article the same way.
- Names (never vary): Jesus → Yesu, God → Nzambe, Christ → Kristo, Adam and Eve
  → Adamu mpe Eva, Peter → Petelo (Catholic Lingala form; the Protestant
  Mokanda na Bomoi uses Piyere — FLAGGED, Jonathan to choose). Aslan, Narnia,
  Lucy, Digory, Tirian unchanged. "Free will" → bonsomi ya kopona ("freedom to
  choose", descriptive — no single Lingala word exists).
- Bible verses: no direct verse quotations appear in these 5 articles —
  paraphrase only, never quoted as Scripture. No direct Lewis quotations either.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
