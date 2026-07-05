# issuebeam.github.io

Marketing site for [Issuebeam](https://github.com/issuebeam/issuebeam) — GitHub Issues from Cursor chat for vibe coders.

**Live:** [issuebeam.github.io](https://issuebeam.github.io)

## Stack

- Jekyll + GitHub Pages
- Tailwind CSS (CDN) + antigravity layout from [qwibo.github.io](https://github.com/qwibo/qwibo.github.io)
- Bilingual: `/it/` and `/en/` with root language redirect

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000 — root redirects to `/it/` or `/en/` by browser language.

## Structure

| Path | Role |
|------|------|
| `_config.yml` | Site metadata, FAQ, CTA URLs |
| `it/`, `en/` | Landing, get-started, about pages |
| `_includes/` | Nav, footer, SEO, FAQ accordion |
| `assets/images/logo/` | Issuebeam SVG logos (violet beam theme) |

Documentation lives in the main repo: [docs/GUIDA.md](https://github.com/issuebeam/issuebeam/blob/main/docs/GUIDA.md) — not MkDocs on this site.

## Related repo

CLI and skeleton: [github.com/issuebeam/issuebeam](https://github.com/issuebeam/issuebeam)
