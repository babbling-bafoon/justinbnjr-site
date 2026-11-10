# justinbnjr-site

Personal blog for Justin Bonjour (N0JBE). Plain black-and-green terminal-style site on GitHub Pages. Domain later: justinbnjr.com (no DNS yet — do not add a CNAME until Justin says go).

## How to add a post

1. Create a file in `_posts/` named `YYYY-MM-DD-short-title.md`  
   Example: `_posts/2026-11-15-first-real-post.md`
2. Put this at the top (edit the title and date):

```
---
layout: post
title: "Your title here"
date: 2026-11-15
---
```

3. Write the post in Markdown under that block.
4. Commit on a branch, open a PR to `main`, merge when it looks good.

Home page lists posts newest-first. RSS updates on its own (`/feed.xml`).

## After first merge

Enable GitHub Pages: **Settings → Pages → Source = Deploy from a branch → Branch `main` / `(root)`**.  
Do not add a CNAME until DNS for justinbnjr.com is ready.
