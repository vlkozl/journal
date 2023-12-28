---
title: "How to make this site in less than 20 minutes"
summary: "About modern ways of making own web site with Static Site Generators."
date: 2023-11-18
author: "Vladimir Kozlov"
---

## Good news

Once upon a time, web development world stood firmly on HTML and CSS shoulders. Then at some point things like WordPress appeared, requiring some skills ~~not to break it up~~ to map everything into it. Blogging platforms like LiveJournal appeared which ended like a really strange places. There were some other blog platforms too. Some were better, some worse. If you, like me, have been ~~sleeping~~ busy with your own things ever since, here's some good news that came from the world of web development by 2023.

## TL;DR

 - Lots of web programming languages and frameworks have emerged or developed since then, thanks to which...
 - Some people invented Static Site Generators, so...
 - Creating a simple yet modern looking blog website is reduced to choosing blog platform, adding up content on it in a convenient [Markdown](https://www.markdownguide.org/) format, and make it run on some hosting.
 - Static site generators do exist, there are many of them (just google), they all work in a similar way. I prefer [Hugo](https://gohugo.io/) for its speed and simplicity and it hosts on GitHub Pages for native compatibility and familiar update workflow.

## Hugo

- Hugo works as a base platform written in [Go](https://go.dev/). It can be installed locally on any machine. With it you starting making a new website.
- Hugo [Theme](https://themes.gohugo.io/) works as a front-end skeleton which your content is visually fit into.
- Site content is written in Markdown and you can use any text editor for it, even VS Code. All site settings are human-readable [YAML](https://yaml.org/) or [TOML](https://toml.io/en/).
- Once installed, Hugo application server is ready to build and run a new site on your machine.
- Write content, make some customization changes, and Hugo will instantly rebuild the site on the fly *in a fraction of a second*.
- Netlify, Cloudflare, Azure Static Web App, GitHub Pages, GitLab — all of those can host Hugo website out of the box. Most of them are free, but some are paid.
- Hugo site works as a Git/GitHub repository. Pushing to main branch triggers publishing to a website directly.

Remember that with your own website you are fully responsible for its content, hosting etc. From other side, there are no specific community rules you have to agree and follow, you don't need to sell your data and transfer its ownership, your content is always yours.

This is it for Hugo. I think everyone finds its own stuff and tools finally and I'm pretty happy with my findings now. Hope this note might be helpful for you to start with static site generators. Personally, I never thought making a nice looking website would be this simple as it is with Hugo. And I love markdown format, so, its fully fit my needs.
