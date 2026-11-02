---
layout: page
title: Plant videos and growing stories
description: Practical plant videos and posts from Hello Plant World. Browse care, propagation, LECA, grow lights and terrarium ideas in any order.
permalink: /plant-videos/
---

A cutting taking root. A potting mix that needs adjusting. A money plant thriving with very little attention. These are the everyday moments I explore with my plants—and share here, one video and post at a time.

I’m **Naren, the creator of [Hello Plant World](https://www.youtube.com/@helloplantworld)**. My examples come from my own collection and growing spaces, with a focus on Indian homes and Bangalore conditions. Take the ideas that fit your plants and adapt them to your own corner of the world.

**Pick a topic that interests you.** Each video is designed to make sense on its own, usually in **1–2 minutes**. Related posts and a shared YouTube playlist connect the ideas when you want to explore further.

{% if site.plant_video_playlist_url and site.plant_video_playlist_url != "" %}
[Watch the playlist]({{ site.plant_video_playlist_url }})
{% else %}
[Browse my YouTube playlists](https://www.youtube.com/@helloplantworld/playlists)
{% endif %}

## Videos and posts

{% assign plant_video_posts = site.categories['plant-videos'] %}
{% if plant_video_posts and plant_video_posts.size > 0 %}
{% for post in plant_video_posts %}
- [{{ post.title }}]({{ post.url | relative_url }}){% if post.description %} — {{ post.description }}{% endif %}
{% endfor %}
{% else %}
Individual video posts will appear here as they’re published. In the meantime, explore the topics and video ideas below.
{% endif %}

## Explore by interest

### Getting a plant home

Choosing a plant for your space, checking it before buying, settling it in, and the simple tools I use.

### Light, windows and balconies

Understanding your growing position, reading humidity and temperature, and noticing when conditions change.

### Pots and homemade mixes

Cocopeat, coco chips, orchid bark, perlite, pumice, charcoal and compost. See what I use, how I measure ratios, and how I adapt a mix.

### Watering and feeding

Checking moisture, using a moisture meter thoughtfully, managing drainage, and measuring fertilizer dilution.

### Repotting and everyday care

Inspecting roots, choosing when to repot, cleaning leaves, pruning, and supporting climbing plants.

### The plants in my collection

Pothos, philodendrons, monsteras, alocasias and anthuriums—their growth habits, care decisions and changes over time.

### Propagation experiments

Cuttings, nodes, divisions, alocasia corms, anthurium babies and air layering. Setup videos and progress updates each tell their own part of the story.

### Figuring out plant problems

Yellow leaves, brown edges, root concerns, pests and suspected nutrient issues. Follow the observations behind a care decision and see what happens next.

### Grow lights and shelves

Choosing lights, arranging plants, using timers and making a growing space easier to maintain.

### Inside my IKEA plant cabinet

The setup, lights, airflow, layout and ongoing maintenance of a cabinet used for tropical plants.

### LECA and low-maintenance money plants

Containers with and without drainage, reservoirs, nutrients and maintenance. I’ll share my money plant’s long gaps between top-ups and the checks behind that particular setup.

### Life with a larger collection

Organizing plants, care rounds, incoming plants, useful records, limited space and time away.

### A small fittonia terrarium

Choosing a container, planting, watching moisture, trimming and maintaining a small closed world.

## Try what interests you

Use the plants and tools you already own. You can try a cutting, mix a small substrate batch, or simply watch how a plant changes. Cabinets, lights and terrariums are projects to explore when they suit your interests and space.

Longer processes appear as several focused posts: preparation, one action, a progress check, or a result. Each includes enough context to watch independently, with related links if you want the wider story.

[Browse the 1–2 minute video ideas](/plant-videos/short-video-plan/) · [See the broader planning notes](/plant-videos/video-plan/)
