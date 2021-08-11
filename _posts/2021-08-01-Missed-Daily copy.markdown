---
layout: post
title:  "I love backups"
date:   2021-08-01 18:32:09 +0000
categories: update next
---

I missed yesterday post : (

I was busy troubleshooting the installation of the Nvidia drivers in my home server. I find really odd how much trouble is to get Nvidia drivers working correctly. I have installed the drivers in my desktop and my eGPU set up, which was a pain on its own, but I thought this is going to be easy since it is a headless server. 

I was wrong. In the first try the drivers could not be installed in one run, because there was an error with the integrated GPU, which did not make sense since I am using a Ryzen 2600 and a GTX 1070 ti. Anyhow, after completing the installation and reboot, I had issues just doing SSH to the server and I lost my DNS settings losing access to Internet. Why on Earth the networking settings are messed up by installing GPU drivers!!!!

I had to restore my configuration using TimeShift, which I appreciate everyday more. I really recommend setting up TimeShift as soon as you have a stable environment. Anyway, I restored the configuration and tried again the installation of the drivers, working with unmet dependencies and after having success with the installation I realized that Docker with support for Nvidia containers was not supported in my OS… Ok, that was my bad, but that is unrelated to the drivers installation experience. This meant I had to do another restoration of my configuration : ) Thanks TimeShift!!!

Maybe I am doing something wrong, but my experience installing Nvidia drivers in Ubuntu is nothing but painful, so remember take a snapshot of your configuration before any change related to Nvidia drivers.

Best!