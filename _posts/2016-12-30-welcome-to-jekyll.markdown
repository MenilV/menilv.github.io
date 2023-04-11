---
layout: post
title:  "Requsting Runtime permissions within Activity vs Fragment"
date:   2016-12-30 16:10:23 +0100
categories: android, permission, runtime
---

As of Marshmallow 6.0 (API 23), Android has introduced runtime permissions model which aditional developers' attention when working with different permission within the application. They are diversified in two sets: `Normal Permissions` and `Dangerous Permissions`. Normal Permissions behave the same why as pre Marshmallow not requiring any user input when using them, but the Dangerous Permissions are on the other a different story.