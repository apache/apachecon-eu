---
title: "Leveraging Groovy and Apache Ignite for fast, distributed, scaleable computing and data"
slug: leveraging-groovy-and-apache-ignite-for-fast-distributed-scaleable-computing-and-data
speakers:
 - Jeremy Meyer
time_start: 2024-06-05 15:20:00
time_end: 2024-06-05 15:50:00
tracks:
 - Groovy
---

Following on from the previous success of distributing Groovy tasks over an Ignite Cluster to solve oddly shaped Rubik’s cubes, we investigate further possibilities using Groovy’s concise and expressive syntax to extend Ignite. This time we take a deeper look at classloader behaviour in the JVM to distribute native Groovy closures. We also extend the Groovy REPL to give us an easy way to fire up nodes in an Ignite cluster and to query data against it. 
 
 
 
 Groovy’s seamless integration with the Java ecosystem makes it the perfect companion to Ignite, allowing developers to prototype their Ignite architecture, send computations to multiple nodes easily, and to write simple but powerful command line prompts to query live data and meta data. 
 
 
 
 In this talk, we will explain the concepts of the Ignite compute grid and data caches, demonstrate this combination of Groovy and Ignite, demonstrate how Groovy can be used to create surprisingly performant results, and report back on progress made since Community over Code NA 2023.