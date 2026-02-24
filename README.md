# 3act Blog

The official blog for [3act](https://3act.app) — the social habit tracker where your crew holds you accountable.

## About

This blog covers accountability, habit formation, productivity, goal setting, and personal growth. It is built with [Hugo](https://gohugo.io/) using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme and deployed via GitHub Pages.

## Tech Stack

- **Static Site Generator:** Hugo (Extended)
- **Theme:** PaperMod (dark mode default)
- **Hosting:** GitHub Pages
- **CI/CD:** GitHub Actions
- **SEO:** Sitemap, robots.txt, Open Graph, Twitter Cards, Schema.org, Apple Smart App Banner

## Local Development

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/YOUR_USERNAME/3act-blog.git

# Run local server
hugo server --buildDrafts

# Build for production
hugo --gc --minify
```

## Adding New Posts

Create a new Markdown file in `content/posts/`:

```bash
hugo new posts/your-post-slug.md
```

Use the following front matter template:

```yaml
---
title: "Your SEO-Optimized Title"
description: "Meta description under 160 characters"
date: 2026-02-24
author: "3act Team"
categories: ["Accountability"]
tags: ["accountability", "habits", "productivity"]
slug: "your-post-slug"
---
```

## Custom Domain Setup

To connect this blog to `blog.3act.app`:

1. Add a CNAME record in your DNS: `blog.3act.app` → `YOUR_USERNAME.github.io`
2. Create a `static/CNAME` file with `blog.3act.app`
3. Enable HTTPS in GitHub Pages settings

## License

Content © 2026 3act. All rights reserved.
