---
layout: post
title: How To Create Posts With Markdown For Jekyll
---
1. The block in between `---` (the YAML front matter) needs to be the first thing in all posts to be recognized by Jekyll.
  1. The `layout` should always be `post` for new posts
  2. full pages have `layout: default`
2. Posts are written in Markdown. Everything possible on the Stack Exchange sites should work here as well. Also there are sweet additions like fenced code blocks.
3. New Posts are dropped in the `_posts` directory and need a certain file format: `YYYY-MM-DD-title-dash-delimited.md`
