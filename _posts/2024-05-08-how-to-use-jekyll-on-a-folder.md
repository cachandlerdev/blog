---
layout: post
title:  "How to Use Jekyll with Github Pages on a Subdirectory"
date:   2024-05-08
categories: websites
---

After spending the last few hours setting up Jekyll with GitHub pages on my static website and trying to figure out why I couldn't get blog entries to show up on `cachandlerdev.github.io/blog/entry1` instead of `cachandlerdev.github.io/entry1`, and deal with the subsequent error messages that kept arising, I finally came to the conclusion that the simplest option was to make a separate repository for the blog.

No, seriously. For anybody who comes across this article in the future who created a GitHub portfolio website and was looking to have a blog located at `url/blog`, but ran into issues with things working fine when building Jekyll locally and GitHub putting the actual blog articles at `url/article1` instead of `url/blog/article1`, just make a new repo called `blog`.
There really are no drawbacks since GitHub pages will publish it under `url/blog`, and realistically, it makes sense to have them separate, because then you don't need to keep rebuilding the main site every time a blog post is created or updated.

I honestly wish I had tried this solution sooner, as it could have saved a few hours worth of troubleshooting to no avail.