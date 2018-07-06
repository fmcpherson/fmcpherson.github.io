---
layout: post
microblog: true
audio: 
date: 2018-04-25 09:07:15 -0400
guid: http://frankm.micro.blog/2018/04/25/i-use-amazon.html
---
I use [Amazon Lightsail](https://aws.amazon.com/lightsail/) to host the Dockerized version of [a CRM application](https://www.monicahq.com/). There has just been a major release and the latest version of the Docker image is not working for me. I take snapshots of the server as a back up, so I was able to revert back to the prior version of the server pretty easily. The process does involve creating a new instance from a snapshot, moving the public IP address to the new instance, and then deleting the old instance. 
