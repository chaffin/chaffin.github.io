---
title: "How to Make Jekyll Look Like Medium"
date: 2026-03-18
layout: single
classes: wide
author_profile: false
read_time: true
comments: false
share: false
related: false
header:
  overlay_filter: 0
  show_overlay_excerpt: false
---

Jekyll is a static site generator that can be configured to closely mimic the clean, distraction-free look of Medium. 

## Why Medium Style?

Medium emphasizes readability:
- Large, readable fonts
- Centered content with limited width
- Minimal visual clutter

This is exactly what we aim to achieve using **Minimal Mistakes**.

### Step 1: Set Layout

Set `layout: single` and `classes: wide` in the front matter. This gives your post:
- A single-column layout
- Wide but centered text
- Minimal distractions

### Step 2: Customize Typography

Add your custom CSS (like font stack, line height, and spacing) to `/assets/css/custom.css`. This ensures:
- Paragraphs are comfortable to read
- Headings stand out clearly
- Images and blockquotes are nicely spaced

### Step 3: Clean Navigation

Previous/Next links can be small inline links for a subtle, Medium-like experience (CSS provided below).

---

> Writing readable, distraction-free content is key for user engagement.

![Jekyll Workflow Diagram](/assets/images/jekyll-workflow.png)
