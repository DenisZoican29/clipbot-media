# clipbot-media

Public static image hosting for Clip Bot's growth-bot `news` strategy montage.

Exists solely so TikTok's Content Posting API can `PULL_FROM_URL` for photo-carousel posts, which requires a publicly accessible URL under a domain/prefix verified in the TikTok developer portal. GitHub Pages' free `github.io` subdomain is used as the verified **URL prefix** (not a full domain) — see `05 System/(C) Growth Bot.md` in the Clip Bot vault project for the full decision record.

- `/media/` — published montage photos (regenerable, not meant to be precious)
- verification file(s) from TikTok's developer portal live at the repo root once issued
