---
layout: post
title: Dataplicity Drastically Simplifies Remote Management of a Raspberry Pi
tags: [tech, raspberry]
---

Typically, if you wanted to control your Raspberry Pi from outside your network, you’d need to go through and set up your router to allow access from the internet, install some software on your Pi, set up a DNS, and cross your fingers you’re doing that all securely. Dataplicity makes this a heck of a lot easier.

Instead of dealing with port forwarding, VPNs, or DNS, Dataplicity essentially grants access to your Pi’s command line from a web app. This way, as long as your Pi is connected to the internet, you can access it from anywhere using Dataplicity’s remote shell web app. Dataplicity doesn’t inherently have root access, but you can grant it manually if you want. There’s even a “wormhole” feature that allows you to create temporary web sites from the Pi, which is especially useful for projects that include streaming video.

You can also easily reboot your Pi, which is helpful if you’re running any type of automation project that might need a little kick in the pants now and again. You can access and manage multiple Pis this way, which could prove useful if you have a bunch of these things in the house. If you’ve ever wanted to connect your Pi to the internet at large, but weren’t comfortable jumping through the security hoops to do so, this is one way to do so that’s easy to manage.
