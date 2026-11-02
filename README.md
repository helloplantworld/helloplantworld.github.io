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

## Plant videos and posts

The [plant video collection](https://helloplantworld.github.io/plant-videos/) presents independent videos and posts, grouped by interest and connected through a shared YouTube playlist.

- `plant-videos/index.md`: public topic hub; published posts with category `plant-videos` appear automatically.
- `plant-videos/short-video-plan/`: separate 1–2 minute plan with discussion points for each video.
- `plant-videos/video-plan/`: broader original idea bank and preparation notes.
- `templates/plant-video-post.md`: copy into `_posts` and complete it for each standalone video. This directory is excluded from publication.
- `_config.yml`: set `plant_video_playlist_url` to the actual shared playlist URL. Until it is supplied, the hub links to the channel’s playlists page.

Each video post should introduce its own context, link its video, and point to the playlist and relevant published posts. Publish and watch in any order. The homepage and main navigation lead to `/plant-videos/`; previous addresses redirect to the appropriate new page.
