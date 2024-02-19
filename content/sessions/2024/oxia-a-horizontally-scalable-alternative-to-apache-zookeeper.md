---
title: "Oxia - A Horizontally Scalable Alternative to Apache Zookeeper"
slug: oxia-a-horizontally-scalable-alternative-to-apache-zookeeper
speakers:
 - David Kjerrumgaard
time_start: 2024-06-05 11:50:00
time_end: 2024-06-05 12:20:00
tracks:
 - Performance Engineering
---

For over a decade, Apache Zookeeper has played a crucial role in maintaining configuration information and providing synchronization within distributed systems. Its unique ability to provide these features made it the de facto standard for distributed systems within the Apache community.
 
 
 
 Despite its prolific adoption, there is an emerging trend toward eliminating the dependency on Zookeeper altogether and replacing it with an alternative technology. The most notable example is the KRaft subproject within the Apache Kafka community,
 
 
 
 While the KRaft project achieved its goal of making Kafka more self-contained by eliminating the need for an external Zookeeper ensemble, the benefits of the KRaft project are limited to the Kafka community.
 
 
 
 This talk introduces Oxia, a subproject within the Apache Pulsar community aimed at providing a horizontally scalable alternative to the traditional Zookeer-based consensus architecture. The goal of Oxia is two-fold:
 
 
 
 Develop a consensus and coordination system that doesn’t suffer from Zookeeper’s horizontal scalability limitations.
 
 
 
 Create a compelling Zookeeper replacement that can be used across the entire Apache ecosystem and just Apache Pulsar.
 
 
 
 This talk will discuss Apache Zookeeper’s inherent scalability issues and demonstrate how Oxia’s architecture is designed to eliminate them entirely. We will also highlight how Oxia’s Java client library makes it easy for projects across the Apache ecosystem to utilize Oxia as a Zookeeper replacement.