# Personal Career Page + Project Blog (Jekyll)

This repo is a simple Jekyll site using the `minima` theme. Customize the files below to get started fast.

## Quick start

1) Update site details in `_config.yml` (name, bio, social links).
2) Create an About page at `about.md`.
3) Add blog posts in `_posts/` using Markdown.

## Suggested file structure

```
/
├── _config.yml
├── README.md
├── about.md
└── _posts/
    └── 2025-01-01-my-first-project.md
```

## Create your About page

Create `about.md` with this starter:

```markdown
---
layout: page
title: About
permalink: /about/
---

Hi, I’m Your Name. I’m a [role] focused on [interests].

What I’m working on:
- Project A: short description
- Project B: short description

How to reach me: you@example.com
```

## Add a project blog post

Create a file like `_posts/2025-01-01-my-first-project.md`:

```markdown
---
layout: post
title: "My First Project"
date: 2025-01-01 10:00:00 -0500
categories: projects
---

## What I built
Short summary of the project.

## Why it matters
What problem it solves or what you learned.

## Links
- Demo: https://example.com
- Repo: https://github.com/your-username/your-repo
```

## Local preview (optional)

If you want to preview locally:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
