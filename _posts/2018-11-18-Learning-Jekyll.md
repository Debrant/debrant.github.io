---
layout:     post
title:      "Learning about Jekyll"
subtitle:   "Discovering Ruby and Jekyll (part 1)"
date:       2018-11-18 17:00
author:     "Debrant"
header-img: "assets/owner/blog/header/post-bg-01.jpg"
thumbnail: /assets/owner/blog/thumbs/thumb01.png
tags: [Webpages, Jekyll]
category: [Jekyll]
comments: false
share: false
---
## Alright, I have decided to see what all the fuss over Jekyll is about .

I have been meaning to add some personal pages to my Github anyway. So
 Jekyll has a [Step-by-step-tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/), but wasn't there yet, as I didn't have [Ruby](https://www.ruby-lang.org/en/).

 Since I have been doing a lot of Yocto and Buildroot work lately, I am on Ubuntu 16.04.5 and was able to follow the [Jekyll on Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/) walk-through. After that it was back to the tutorial, which was by and large one of the easiest, but most helpful I have seen.

 Next I looked for a cool [theme](http://jekyllthemes.org/), and fell in love with several, but my top two were [Moon](https://taylantatli.github.io/Moon/) and [MAD4Jekyll](http://madforjekyll.github.io/). In the end I chose the MAD4Jekyll theme and found that I needed to install the  jekyll-paginate gem.


 ### Where does the build really happen?

 It can be a little tricky figuring out where and how Jekyll is populating information when going from a very simple site (like in the tutorial) to a monster like MAD4Jekyll. My first attempts to get the MAD4Jekyll theme failed to pull over all of my edits.



 I quickly realized is how easy it is to end up making changes in the wrong path. The _site folder is generated from sources when **jekyll build** or **jekyll serve** are issued.
