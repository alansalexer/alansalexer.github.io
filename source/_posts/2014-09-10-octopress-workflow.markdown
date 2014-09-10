---
layout: post
title: "Octopress workflow"
date: 2014-09-10 17:33:54 +0800
comments: true
categories: [codeforces,python]
---
OK, after we set up an Octopress blog, here's the basic workflow to create blogs and publish them to Github Pages:

* rake new_post["your_title"]
* Open the file located in /source folder and start composing
Either Sublime-Text or 
* rake generate
* rake deploy
* git add . -A && git commit -m "upload some post" && git push origin source

A little explanation: we still need the dirty Git operations because this saves our works to ```source``` branch, while ```rake deploy``` only push stuff to master branch for display.