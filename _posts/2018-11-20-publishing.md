---
layout:     post
title:      "Publishing my first pages"
subtitle:   "Discovering Ruby and Jekyll (part 2)"
date:       2018-11-20 12:00
author:     "Debrant"
header-img: "assets/owner/blog/header/post-bg-02.jpg"
thumbnail: /assets/owner/blog/thumbs/thumb02.png
tags: [Webpages, Jekyll]
category: [cat01]
comments: false
share: false
---
#  The details

Last time I failed to keep all of my work in the correct directory,  clearly the skills I learned in the tutorial needed a little boost. Luckily I work from my Github, and after a couple times of being forced to `git reset [sha]` I had sufficiently shamed myself into setting up my [Atom editor](https://atom.io/) to project mode out of my git folder.


![better](/assets/owner/blog/body/better.bmp){: align="left"}  For me the easiest way to do this is to open atom from the terminal, which will give you a nice colorized tree.

   `atom debrant.github.io/`

Additionally you can notice that the _site and the .git folders are shaded out, meaning Atom knows this these are not working directories. If somehow you end up making changes there anyway, you will notice that you can't stage them properly.

### No CSS

Great everything looks great on http://localhost:4000, but after pushing up to my repo it lookslike this.
![No CSS](/assets/owner/blog/body/oops.png)

A review of the debug console eventually showed that the original repo was all http: and now my pages won't display with mixed  content. A fast find and replace and I am up and running.

### Next time

I am going to find a way to make all of the images in the slider gallery the same height, and then fix the search element.
