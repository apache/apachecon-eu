---
title: "Apache Ratis - A High Performance Raft Library"
slug: apache-ratis-a-high-performance-raft-library
speakers:
 - Tsz-Wo Nicholas Sze
time_start: 2024-06-03 15:20:00
time_end: 2024-06-03 15:50:00
track: Big Data Storage
day: 1
timeslot: 11
room: Rhapsody

---

Apache Ratis is an open source Java library for the Raft Consensus Protocol. Raft is being used successfully as an alternative to Paxos to implement a consistently replicated log. Raft is proven to be safe and is designed to be simpler to understand. Ratis is a high performance implementation of Raft. Apache Ozone, Apache IoTDB and Alluxio use Apache Ratis for providing high availability and replicating raw data.
 
Ratis implements all the standard Raft features, including leader election, log replication, membership change and log compaction. Moreover, it is designed with data intensive applications in mind and fully supports asynchronous event-driven applications. It is highly customizable -- allows pluggable state machines, pluggable RPC, pluggable Raft log and pluggable Metrics. It has been implemented to provide low latency and high throughput on transactions.
 
In this talk, we first give a brief introduction of Raft. We will discuss the features and use cases of Ratis. Finally, we discuss the current development status and the future work.