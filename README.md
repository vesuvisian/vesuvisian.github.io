# vesuvisian.github.io

Source for [vesuvisian.github.io](https://vesuvisian.github.io) — a personal blog covering code, technology, and other musings.

Built with [Jekyll](https://jekyllrb.com) and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, hosted on GitHub Pages.

## Local Development

**Prerequisites:** Ruby and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Adding a Post

Create a file in `_posts/` named `YYYY-MM-DD-title.md` with the following front matter:

```yaml
---
layout: single
title: "Post Title"
date: YYYY-MM-DD
tags: [tag1, tag2]
header:
  image: /assets/images/your-image.png
  teaser: /assets/images/your-image.png
---
```

Post content goes below the front matter in Markdown.

## Structure

| Path | Purpose |
|---|---|
| `_posts/` | Blog posts |
| `_pages/` | Static pages (About, Contact, etc.) |
| `assets/` | Images, PDFs, JS, and 3D models |
| `_includes/` | Custom HTML includes (overrides theme defaults) |
| `_layouts/` | Custom layout overrides |
| `_config.yml` | Site-wide configuration |
