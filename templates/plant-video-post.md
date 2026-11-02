---
layout: post
title: "Replace with one plant question or task"
date: YYYY-MM-DD HH:MM:SS +0530
categories: [plant-videos]
description: "One sentence about what this video shows."
video_url: ""
---

<!-- Copy to _posts/YYYY-MM-DD-your-video-title.md. Fill in the date, title, description and video_url before publishing. This template directory is excluded from the site. -->

One short paragraph introducing the question and the plant or setup shown. Make this post understandable without watching another video first.

{% if page.video_url and page.video_url != "" %}
[Watch this 1–2 minute video]({{ page.video_url }})
{% endif %}

## What I’m showing

- The starting conditions that matter.
- The single action or observation in the video.
- What I’ll check next, if this needs time.

## My setup

Name the plant, container, materials and relevant conditions. Include exact ratios or product directions only when they are part of this demonstration.

## Keep exploring

{% if site.plant_video_playlist_url and site.plant_video_playlist_url != "" %}
[Watch the shared playlist]({{ site.plant_video_playlist_url }})
{% endif %}

[Browse plant videos and posts]({{ '/plant-videos/' | relative_url }})

<!-- Add descriptive links to published related posts or updates here. -->
