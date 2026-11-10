# justinbnjr-site

Personal blog for Justin Bonjour (N0JBE). Plain black-and-green terminal-style site, meant for GitHub Pages. Domain later: justinbnjr.com (DNS not set up yet).

## How to add a post

1. Create a new file in `_posts/` named like `YYYY-MM-DD-short-title.md`  
   Example: `_posts/2026-11-09-hello-world.md`
2. Put this at the top of the file (edit the title):

```
---
layout: post
title: "Your title here"
date: 2026-11-09
---
```

3. Write your post in Markdown under that.
4. Commit, push a branch, open a PR to `main`, and merge when you're happy.

That's it. The home page lists posts newest-first. The RSS feed updates automatically.

## After first merge

Enable GitHub Pages for this repo: Settings → Pages → Source = Deploy from a branch → Branch `main` / root (or `/docs` if you move it). Do not add a CNAME until DNS for justinbnjr.com is ready.
