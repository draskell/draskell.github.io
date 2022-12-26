---
title: "Introduction"
date: 2022-12-26T10:39:35-08:00
draft: true
---

# Welcome to my blog

Welcome, I am using this blog to explore my interests. Anything that excites me enough to keep me up into the wee hours tinkering. Hence the title NightNoon, as in "Should I go to bed? No! It's barely night noon."

The site is built using Hugo which will serve as the first topic to explore for the blog. I'm taking a page from [Simon Willison](https://simonwillison.net) who has suggested blogging in bite size chunks and starting with TIL posts.

# Hugo TIL

This will be my first TIL post about how I made this site with Hugo.

## Getting started

[Hugo](https://gohugo.io) is a simple static site generator written in GoLang with a wide range of open source themes available. This site is using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

Getting started is as easy as: 
1. Installing hugo `brew install hugo` 
1. Making a new project `hugo new site <SITE-NAME> -f yml`
1. Initializing the newly created project directory as a git repository
```
cd <SITE-NAME>
git init
```
1. Check out a [theme](https://themes.gohugo.io) as a submodule, for this site we're using PaperMod: 
```
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```
1. See your new site with `hugo server` then go to http://localhost:1313.

## Next steps

### Make a favicon

I made the simple favicon for this site using a [favicon generator](https://favicon.io/favicon-generator/). Unzip the download into the `<SITE-NAME>/static` directory.

### Customize the theme

Follow the directions in the theme to customize your site to your liking. In this case for PaperMod I chose to use profile mode and added an image for the landing page.