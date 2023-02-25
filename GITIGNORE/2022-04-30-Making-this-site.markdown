---
layout: post
title:  "Making this site"
date:   2022-04-30 23:23:00 +0100
categories: portfolio
---

The source code for this website lives in a Git repository [stored on GitHub](https://github.com/mmguinness/portfolio). GitHub Pages allows me to host a website directly from this repo.

I also used Jekyll, a static site generator to add a header and footer to my pages, it takes Markdown and HTML files and creates pages based on my layout.

Each time I push a new commit to the main branch, GitHub Pages sees this and starts a new build, which generates a new set of static web pages.

Hugo and Netlify seemed like another good option for hosting a simple static website, for ease I went with a Ruby based option, as I am more familiar with this environment. 

To get things up and running, I referenced [the programming historian blog](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages), [GitHub Pages Docs](https://docs.github.com/en/pages) and [Jekyll Docs](https://jekyllrb.com/docs/).

