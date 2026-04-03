# Conwair

Construction blog and tools by The Mason. Built with Jekyll, hosted on GitHub Pages.

## Local development

```
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Adding a new post

Create a file in `_posts/` with the format `YYYY-MM-DD-title-slug.md`:

```
---
layout: post
title: "Your Post Title"
date: 2026-04-03
author: The Mason
tags: [opinion, review, guest, or news]
excerpt_custom: "A short description that shows on the homepage."
---

Your content here. Write in markdown.
```

## Deploying

Push to `main` branch on GitHub. GitHub Pages builds and deploys automatically.

Make sure GitHub Pages is enabled in your repo settings and set to build from the `main` branch.
