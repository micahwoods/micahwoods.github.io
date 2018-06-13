---
layout: post
title: "Posts are now tagged by topic"
share-img: "https://www.asianturfgrass.com/img/mtt_nov.jpg"
tags: [web/tech, turf info]
bigimg:
- "/img/mtt_nov.jpg"   :  "seashore paspalum at Muang Thong Thani, Thailand, November"
---

I *finally* figured out how to link the tags on the "new" ATC site into lists of posts, tagged by topic. More about that below. What this means is if you see a tag for [soil (10 posts)](https://www.asianturfgrass.com/tags/#soil) or [water (2 posts)](https://www.asianturfgrass.com/tags/#water) or [tissue testing (4 posts)](https://www.asianturfgrass.com/tags/#tissue+testing) or [awesome (1 post)](https://www.asianturfgrass.com/tags/#awesome), you can click directly on the link and it will bring you to a list of all the posts on the site tagged with that same topic.

You can also go directly to the [post archive](https://www.asianturfgrass.com/tags/) page, indexed by topic, to browse through them all at once.

This is basic functionality for most blogs---see for example the [archive and tags of the Viridescent blog](http://www.blog.asianturfgrass.com/archives.html)---but when I switched the ATC site over to [Jekyll](https://jekyllrb.com/), I wasn't able to get the tags working. Because of that, I put tags on the posts, but they weren't linked to anything, and the posts were not gathered onto an archive page.

I was able to make the updates today by using the instructions and code from [Pavel Dmytrenko's post about implementing tags](http://pavdmyt.com/how-to-implement-tags-at-jekyll-website/). Like Pavel, I also used [CSS tags by Wouter Beeftink ](https://codepen.io/wbeeftink/pen/dIaDH).

---

You may also notice that thanks to an update for custom domains on GitHub pages, this site is now [served only over HTTPS](https://blog.github.com/2018-05-01-github-pages-custom-domains-https/).
