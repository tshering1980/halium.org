---
layout: post
title:  "Halium is in the air!"
date:   2017-04-24 10:07:34 +0530
categories: announcements
---

## Preface

Over the years, various efforts have been made to bring the GNU/Linux to mobile devices for example, Maemo, Meego, Mer, SailfishOS, Ubuntu Touch, Plasma Mobile and have achieved their individual goals or are working in direction of achieving them.

During the development of such projects it was suggested multiple times that this communities should work together as their ultimate goal is the same. However due to various reasons this never happened in the past. However we believe that it is time to change this situation.

## Introducing Project Halium

Currently distributions like AsteroidOS, LuneOS, Mer, Plasma Mobile, SailfishOS, Plasma Mobile and Ubuntu Touch have one thing in the common that they use the libhybris to interact with the android binary blobs and they also run the various android daemons using different methods. And there is lot of fragementation on how this task is handled even though this parts don't need to be different as their essential goal is to make use of android binary blobs.

Project Halium is the effort by the community which aims to bring the common grounds for different distributions and have a common base which includes the Linux kernel, Android Hardware Abstraction Layer, and libhybris. Project Halium also aims to standardize the middlewares used to interact with the hardware of device. By having this parts shared, we believe that it will reduce the fragmentation we have currently.

## Development Plan

At the time of writing this announcement Project Halium exists merely as a draft document to which multiple developer contributed. However we have come up with development plan or outline which will help you to understand what to expect in upcoming time.

Initially Halium team wants to work on the proof-of-concept android image which can be reused by more then one distibutions for this we will use the Nexus 5 (hammerhead) as a reference device.

## Why another standard?

From the time communnity was informed of the project, we were asked the question on why this new effort/standard is needed when there is already xyz distribution and were pointed to this xkcd strip,

![xkcd standards](https://imgs.xkcd.com/comics/standards.png)

However Project Halium wants to see the comic as below,

![xkcd standards final](http://static.davidedmundson.co.uk/blog/standards_final.png)

(Credits to David Edmundson from KDE for this comic)

To explain further, Project Halium doesn't aim to replace any of the phone distributions that are currently available but wants to be part of them. Project Halium is aiming to be the common platform that can be reused by this communites. 

## Who are we?

Currently Project Halium team is formed of,

- Bhushan Shah (KDE contributor, Plasma Mobile maintainer)
- Marius Gripsgard (UBports founder and maintainer)
- Next could be you.. ;)

## Still have questions?

Project Halium team plans to do AMA on reddit at xx/xx/xxxx xx:xx UTC, join us or ask questions in the comment box below.