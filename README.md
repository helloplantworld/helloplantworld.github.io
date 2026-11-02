# Hello Plant World

A Jekyll blog with custom layouts built on Minima, published with GitHub Pages.

Website: https://helloplantworld.github.io/

GitHub Pages publishes `main` and `/ (root)` from the `helloplantworld.github.io` repository.

Edit `index.md` for the homepage and `about.md` for the About page. Add posts to `_posts/YYYY-MM-DD-post-title.md` with `layout: post`, a title, and a date in YAML front matter. Push to `main` to publish.

The brand palette in `assets/main.scss` uses dark green `#203d32`, butter yellow `#f2d68a`, paper `#f5f0e6`, and ink `#24352c`. Display headings use the locally hosted Anton font; its license is in `assets/fonts/OFL.txt`.

For local preview, install Ruby and Bundler, then run `bundle install` and `bundle exec jekyll serve`. Open http://localhost:4000.

## Publish an article

On GitHub, choose **Add file → Create new file** and name it `_posts/YYYY-MM-DD-your-title.md`. Start with this front matter, then write the article in Markdown:

```markdown
---
layout: post
title: "My first plant story"
date: 2026-11-01 09:00:00 +0530
---

Your introduction goes here. This first paragraph becomes the homepage excerpt.

## What I learned

Write the rest of your article here.
```

Use today's date or an earlier date to publish immediately. Future-dated posts appear only after a build runs after their publication time. Commit to `main` to publish automatically. Sign in as `helloplantworld` for edits on GitHub.

To use a cover photo, add it under `assets/images/` and set `image: /assets/images/your-photo.jpg` and `image_alt: "Describe the photo"` in the front matter. The latest article's cover also appears on the homepage; without a cover it uses the botanical illustration.

For local commits, follow the contribution identity in `AGENTS.md`.

## Course outline

Navigate the complete indoor-growing course at [helloplantworld.github.io/course-outline/](https://helloplantworld.github.io/course-outline/). It contains 73 videos across 13 modules, with discussion points, equipment lists, optional demonstrations, and Shorts/Reels ideas.

Edit `course-outline/index.html` for the published page and keep `course-outline/course-outline.md` in sync as its downloadable text edition. The standalone HTML is served directly by GitHub Pages; its module navigation and lesson anchors work without JavaScript. The course link appears in the site header.

The [learner course overview](https://helloplantworld.github.io/course-outline/overview/) explains learning outcomes, the progression through all 13 modules, and optional practicals. Edit `course-outline/overview.md` for that page. The homepage and main navigation lead to this overview; the detailed creator outline remains at `/course-outline/`.
