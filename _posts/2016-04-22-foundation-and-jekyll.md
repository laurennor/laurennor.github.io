---
layout: post
title:  "Foundation 6 and Jekyll 3 Site Redesign!"
categories: jekyll foundation
---
My new site is finally live and there was certaining a bit of a learning curve on getting used to sass and foundation. I've never used foundation before but decided to use it instead of bootstrap. I have never been someone who turned down a good challenge and it was one especially with customizations. [Foundation 6][foundation-6] is fairly new so I had to rely heavily on its documentation since there was not a lot of information on it beyond the official site.

I stumbled upon a nifty tutorial for getting started with the foundation & jekyll combo on the [Penguin Dreams][penguin-dreams] site. The site also included the [Jekyll Foundation][jekyll-foundation-gh] repo on github. I found it very useful to getting started but ending up in a bit of a bind with my _global.scss and _main.scss.

I reached out to one of my favorite slack channels for answers as to why my customizations were being overrided by _global.scss. In the process, I learned a lot more about how sass worked as two people reached out to me to try to resolve my issue. It turned out that I was giving the foundation.scss file which @import 'global' too much control so whenever I used 'jekyll serve' it would default to global settings. I learned a lot from this problem and I was thrilled to have support from [LWC][lwc] ladies who helped walk me through some things I didn't know about sass imports and includes.

[jekyll-docs]: http://jekyllrb.com/docs/home
[foundation-6]: http://foundation.zurb.com/sites.html
[lwc]: http://lwc.tech/
[penguin-dreams]: http://penguindreams.org/blog/jekyll-3-and-foundation-6/
[jekyll-foundation-gh]: https://github.com/sumdog/jekyll-foundation