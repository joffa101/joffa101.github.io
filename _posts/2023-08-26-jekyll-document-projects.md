---
title: Documenting My Projects with Jekyll and GitHub 
date: 2023-08-25
catagories: [projects,software]
tags: [github,jekyll,documentation]
---


#Documenting My Projects with Jekyll and GitHub 

This is how I have set up my Documentation site: https://joffa101.github.io, http://docs.geofflamb.com
Mostly using https://technotim.live/posts/jekyll-docs-site/ and https://www.youtube.com/watch?v=5z7_qp0CWBY

Source live in https://github.com/joffa101/joffa101.github.io
Locally lives in /Users/glamb/Documents/src/GitHub/joffa101.github.io

#Getting push to work

```bash

cd /Users/glamb/Documents/src/GitHub/joffa101.github.io

JEKYLL_ENV=production bundle exec jekyll b
bundle exec jekyll s #build locally

git add --all
git commit -m "insert comment here"
git push


```

