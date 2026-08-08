# kavish110.github.io

Personal portfolio site, built with Jekyll and hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Adding a blog post

Create a new file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-08-07
---

Post content in Markdown goes here.
```

It will automatically show up on the [/blog](/blog) page.

## Deploying

Push to the `main` branch of this repo (`kavish110/kavish110.github.io`) on
GitHub. GitHub Pages will build and publish it automatically at
https://kavish110.github.io.
