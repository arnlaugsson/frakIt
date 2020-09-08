---
title: Blogging like it's 1999
date: "2020-09-08"
description: "How to build a blog, and develop on the iPad."
layout: layouts/post.njk
---

So I knew I wanted to use my iPad for this learning experiment, which means that I need the technical stack that works on a mobile device. Mind you; I have a 2018 iPad Pro with a very lovely foldable keyboard.

I signed up for a [CodeSandbox](codesandbox.io) account some weeks/months before. I have been happy with up until now. But I soon encountered some issues on the iPad. Including, but not limited to:

1. Copy/paste functionality is missing, not broken but entirely missing.  There probably are some workarounds, but I need to have it working on the keyboard.
2. Git branching does not work on CodeSandbox. If I make changes and add those changes, I can either push directly to my main branch or create a PR and be stuck on that branch forever on that sandbox.

These are the two main reasons I decided to search for other solutions. After some digging, I discovered [GitPod.io](http://gitpod.io/). I tried it, and it seems to work; at least, I did not have the same two issues as above.

So my Technical stack is settled.

- Blog framework: [Eleventy - 11ty](https://www.11ty.dev)
  - A straightforward static site generator.
  - I opted to create my folder structure for the blog posts, using years and months to separate posts.
- Code editor: [gitpod.io](https://gitpod.io)
  - One caveat; make sure to give it the proper permissions.
- Code hosting: [Github](https://github.com)
  - I might change this later on to have a comparison, but I like how Github works.
- Deployment and hosting: [Netlify](https://www.netlify.com)
  - Seamless integration and setup; works out of the box.

So after posting this blog, I can say that this has been my first learning experiment. And I am happy with the results.

Stay tuned.
