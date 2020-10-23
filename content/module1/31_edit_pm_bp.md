---
title: "Edit the promotion manager blueprint"
date: 2020-10-15T18:47:14+03:00
weight: 31
draft: false
---

* target property: change the mapping of the applications to the underlying infra. Current 3 VM map to 1 VM to save cost for the initial test phase.​

* Instances: change the number of instances that are created the UI server (front end) in the promotions manager app. Scale out. We want to do load testing so we will add more instances of the UI web server that will be load balanced using AWS ELB​

* Once saved, it will be automatically synced to your Colony space