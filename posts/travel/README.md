# Travel Stories

This directory contains travel blog posts that will appear on the Travel page.

## Structure

Each travel story should be in its own subdirectory with:
- `index.qmd` - The blog post content
- `featured.png` or `featured.jpg` - Featured image
- Any additional images referenced in the post

## Example Directory Structure

```
posts/travel/
  2025-12-sri-lanka/
    index.qmd
    featured.jpg
    beach.jpg
    temple.jpg
```

## Front Matter Template

```yaml
---
title: "Your Travel Story Title"
description: "A brief description of your trip"
author: "Jonas Samuelsson"
date: "2025-12-15"
image: featured.jpg
draft: false
---
```

Your travel story content goes here with markdown formatting, photos, and narratives about your adventures.
