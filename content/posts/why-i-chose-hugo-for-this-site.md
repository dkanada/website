---
title: "Why I Chose Hugo for this Site"
date: 2018-06-11T15:49:54+09:00
---

I recently decided to make a small blog for ocassional ramblings, and as usual I spent the next two weeks researching everything even remotely related to creating a blog. I would hate to just dive in and have to move everything to a different framework later if I found a better solution. The opposite end of the spectrum is spending too long doing research about a topic instead of actually implementing an idea. I wish I could say that I never fall into that category, but unfortunately it's the exact opposite. Two months had already gone by before I finally chose Hugo and got everything set up for this website.

### The Research

After doing a small amount of research, I had three requirements for the platform I wanted to use.

1. No web frameworks or massive javascript libraries
2. Some level of automation should be available for blog creation
3. The software should be able to run on my own servers

A static site generator seemed like the best solution, and Jekyll and Hugo are the most popular, so I started delving into the documentation for both. The initial thing that drove me away from Jekyll was the ruby dependency. Jekyll has a huge amount of plugins available through the RubyGems repository. I have absolutely no clue why I would use any plugins for this site, and I don't like using unnecessary package managers when I can avoid it. I also vastly preferred the directory layout for Hugo. Jekyll uses two separate folders for drafts and posts, whereas Hugo simply has a file property in the metadata that can be toggled on before a post is complete. Rather than a single folder for posts, Hugo just has a parent folder below which any number of subdirectories can be created. This seems much more useful and supports lots of edge cases like running two separate blogs easily on the same site, which I intend to do at some point in the future.

> Did I mention the entire reason I created this site was to rant somewhere about how amazing the movie [Edge of Tomorrow](https://www.imdb.com/title/tt1631867/) was? Seriously, go watch that movie right now, what are you doing?

### The Decision

Both projects have theming support, but for this site I chose to make a simple theme on my own. I almost went with a modified theme inspired by PureCSS by Yahoo that you can see below, but I am partial to dark themes. The styling will probably change often, I am always finding interesting new site layouts on other blogs.

![purecss](/images/purecss.png)

Jekyll basically has too many features that only add complexity. In addition, Hugo fixes several small annoyances I found when learning about Jekyll and implements them in a more logical way.
