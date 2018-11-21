---
layout: post
microblog: true
audio: 
photo: 
date: 2018-07-20 09:28:08 -0500
guid: http://frankm.micro.blog/2018/07/20/azure-has-a.html
---
[Azure has a different approach to static sites](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-html) because it associates a VM to the site rather than storage. The big difference is that you can't associate a custom domain to the free tier, you will have to pay for the VM and it looks like you will need to buy a certificate. The upside to this approach is that you can implement SSL without having to use a CDN.
