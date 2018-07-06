---
layout: post
title: "Tweeking CSS "
microblog: false
audio: 
date: 2017-12-16 17:42:31 -0400
guid: http://frankm.micro.blog/2017/12/16/tweeking-css.html
---
Ok, after some fiddling I now have the home page rendering as I want it to on tablets. First I experimented with the viewport setting, but that did not fix the problem. Next, I downloaded the CSS and uploaded a copy to my server. Then, I experimented with the [@media](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) setting, landing on auto for the left and right margins and max-device-width to 1024px. 

Now the home page renders centered on my iPad Mini, Nexus 9 and iPad Pro. It actually renders the best on the Nexus 9. 
