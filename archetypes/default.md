---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: { { .Date | time.Format "2006-01-02" } }
author: Author Name
summary: Summary
tags: [""]
draft: true
cover:
  image: image.jpg
  alt: alt text
  caption: caption
  relative: false
  hidden: false
audio:
  src: audio.mp3
  caption: caption
  hidden: true
---
