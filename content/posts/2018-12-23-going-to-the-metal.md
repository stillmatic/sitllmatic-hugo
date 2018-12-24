---
title: Going to the Metal
author: ~
date: '2018-12-23'
categories:
  - notes
slug: going-to-the-metal
---

A year and a half ago I rebooted this blog using R's Blogdown and Hugo. I thought at the time that this was a good choice, because it let me use a static site generator (aka just write Markdown), while still offering syntactic sugar and scaffolding. "Batteries included," if you would.

The two big reasons I spent a day migrating to a raw metal Hugo installation:

* The compile and deploy process that was hacked together to work with R and Travis broke on me. That's the simplest reason, I could write new posts but they weren't getting picked up by the Hugo binary, and thus weren't compiled to the homepage and I gave up investigating.
* I don't really write R code much anymore. Quora uses Python exclusively (for engineering and data science), so the closest I get to R is by making graphs in Plotnine. I did one analysis last year using R because I needed to do an ordinal regression and there wasn't a Python library, but that's a pretty rare case.

Hopefully using Hugo alone will be a lighter-weight process for me to write more!