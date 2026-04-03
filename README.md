# David Letscher Blog

This repository contains a Jekyll-based personal blog for `davidletscher.github.io`.

## What's included

- A custom homepage and blog post layout
- A working Jekyll config and feed
- A sample post
- Lightweight custom styling
- GitHub Pages-friendly structure

## Project structure

- `_config.yml` - site configuration
- `_layouts/` - shared page templates
- `_posts/` - blog posts
- `assets/css/style.css` - site styles

## Local development

Install Bundler if needed, then run:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

## Writing a post

Create a new file in `_posts/` using this format:

```text
YYYY-MM-DD-title.md
```

Example:

```text
2026-04-02-my-next-post.md
```

Each post should start with front matter such as:

```yaml
---
title: "My Next Post"
date: 2026-04-02 09:00:00 -0500
---
```
