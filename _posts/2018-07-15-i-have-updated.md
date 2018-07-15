---
layout: post
microblog: true
audio: 
date: 2018-07-14 23:02:13 -0400
guid: http://frankm.micro.blog/2018/07/15/i-have-updated.html
---
I have updated [my profile page](https://frankm.org/) and learned something about content delivery networks along the way. I host my profile in a S3 bucket that I have now configured for HTTPS. The only way to use Amazon’s SSL certificate is by using their CDN, Cloudfront. 

The fun begins when you make changes to said web page and they never seem to appear, even though you know for certain the latest version of that page is in the bucket. Turns out you need to invalidate that page in the Cloudfront console to force it to be refreshed in the cache. Along the way I made changes to the TTL for the page. 

All fun geeky stuff, but really too many hoops to serve a simple web page with one picture. 
