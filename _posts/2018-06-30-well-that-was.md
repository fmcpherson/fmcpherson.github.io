---
layout: post
microblog: true
audio: 
date: 2018-06-30 13:41:47 -0400
guid: http://frankm.micro.blog/2018/06/30/well-that-was.html
---
Well, that was interesting. I updated my Pi3 with the latest release of Raspbian and then decided to clone my new Jekyll repo and edit [the about page](https://writing.frankmcpherson.net/about/) on my Raspberry Pi. Just because I could. I committed and pushed the update to the repo and checked the about page on the new site, and the new edits did not appear. Went to the Netlify site, logged in, and found the deploy failed with some error relating to node. I think during deploy nodejs 8 was attempted to be installed and it failed. 

Next, I tried a fresh re-deploy and selected clear cache and this time deployment was successful. 

So, what I learned here is that it appears whenever Netlify sees and pulls an update from the repo it seems to rebuild the container/VM that is hosting the site that includes installing nodejs, installing ruby gems (Jekyll uses ruby) then does a Jekyll build and ultimately deploys the site from the site fielder.
