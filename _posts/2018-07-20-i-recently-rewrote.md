---
layout: post
microblog: true
audio: 
photo: 
date: 2018-07-20 13:50:42 -0500
guid: http://frankm.micro.blog/2018/07/20/i-recently-rewrote.html
---
I recently rewrote [my profile page](https://frankm.org) and implemented HTTPS using Amazon S3 and Cloudfront.  In my opinion S3 provides one of the easiest and least expensive ways to host a simple, static web site. Unfortunately HTTPS adds complexity, both in what you need to do to build the site and also in how you maintain it. 

I did a brief survey and I think that that the simplest way to set up a web site with HTTPS is to host with a service like [Bluehost](https://www.bluehost.com), which provides a free SSL certificate. [Bluehosts's $8.99/month price](https://my.bluehost.com/hosting/help/141#shared) is reasonable, but not as cheap as Amazon for a really small site like mine, which is a single HTML page.

So, in my opinion with the current push to HTTPS,  you are better off going with a service provider that includes HTTPS as part of the service. If you are more technical and willing to fiddle with things, you can save money with S3/Cloudfront. 
