---
title: "The Unified Compaction Strategy in Cassandra 5"
slug: the-unified-compaction-strategy-in-cassandra-5
speakers:
 - Branimir Lambov
time_start: 2024-06-03 14:40:00
time_end: 2024-06-03 15:10:00
track: Cassandra
day: 1
timeslot: 10
room: Symphony
---

Choosing a compaction strategy for a Cassandra database has historically been a very difficult problem, where making the wrong choice can have lasting effects on performance while making a change later is a time-consuming and costly process.
 
The Unified Compaction Strategy, introduced with Cassandra 5, is designed to provide a solution to this problem by effectively handling a diverse range of use cases, including those best suited for leveled, tiered, and time-windowed compaction. It addresses the limitations of previous strategies, improves concurrency, and allows for easier switching or reconfiguration without extensive recompaction. The approach is based on a flexible target state abstraction that covers the range of behaviours of the existing strategies, and the concept of SSTable “density”, the ratio between its size and the range of tokens that it covers, that enables the splitting data in an increasing number of shards as it reaches higher levels of the hierarchy. Crucially, the new strategy can understand and work with the hierarchies constructed by the legacy levelled and size-tiered strategies, enabling a seamless upgrade process.
 
 
 
 This talk will describe the ideas behind the solution, its usage and configuration, as well as its practical use in managing higher node densities.