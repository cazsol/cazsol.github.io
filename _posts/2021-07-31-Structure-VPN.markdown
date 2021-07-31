---
layout: post
title:  "Working on the VPN - Part 1"
date:   2021-07-31 03:16:09 +0000
categories: update next
---

Yesterday I started working on setting up my VPN in my Raspberry Pi. Fortunately or unfortunately I used PiVPN to set up the VPN, which made the initial set up quite easy, however when I tried to set up a different network interface to route the traffic I had problems, based on the automated configuration that PiVPN does. 

PiVPN as a tool is great to set up a VPN in one go, however it is not really clear the type of configuration that it does in the background and you lose visibility on how to modify certain parameters when needed. I would use it again in the case that I am fully clear of what my final set up would look like, but in case you are experimenting it might be easier to go through the manual configuration yourself to understand what happened and how you can change it later if needed.

Another topic that I am working now is trying to increase the speed of the VPN. I have tried Open VPN running on my home server and directly on my router (Yei! I did not know the router could do that), and WireGuard on the Raspberry pi, however I cannot get more than 10 Mbs in any configuration. I find this limited to the use case I am trying to put together, but will keep trying.

On the side, I am working on the write up to set up the VPN. 

Keep coming!