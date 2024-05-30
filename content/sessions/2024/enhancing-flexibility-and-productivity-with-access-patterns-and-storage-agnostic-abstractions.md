---
title: "Enhancing Flexibility and Productivity with Access Patterns and Storage-Agnostic Abstractions"
slug: enhancing-flexibility-and-productivity-with-access-patterns-and-storage-agnostic-abstractions
speakers:
 - Jan Lukavský
time_start: 2024-06-04 12:30:00
time_end: 2024-06-04 13:00:00
track: Data Engineering
day: 2
timeslot: 7
room: Rhapsody
---

This session will introduce a platform created to bridge the existing gaps in data management while removing some of the complexities in existing Big Data ecosystem. The platform is built around a comprehensive data model describing structured entities and their relations. The model is consistently applied across three abstract types of storages - streaming (e.g. Apache Kafka, Google Cloud PubSub), batch (e.g. Hadoop HDFS, S3, Google Cloud Storage) and random-access (e.g. Apache Cassandra, Apache HBase, Google Cloud BigTable). The platform ensures eventual consistency between all these types of storages by replicating data flowing from streaming (commit-log) sources into other types. By using abstractions over these storage types, it enables running multiple instances of applications not only in different regional zones, but also across different technologies (e.g. cloud vs on-premise) without the need to change the application code. The platform also provides sources and sinks for data processing engines like Apache Beam or Apache Flink, so that sophisticated data transformations can be easily integrated into the platform as well, leveraging all the guarantees of the platform.
 
 
 
 Although the platform has eventual consistency at its heart, due to the applied data model, the platform can build strong ACID guarantees, applied across different storage types. The abstraction layer also simplifies development due to simple local testing of complex scenarios where all storages can be replaced with in-process canonical representations. This greatly improves the ability to focus on implementing the application logic and postpone decisions about technological choices until runtime and subject to actual application's needs (which can easily change over time).
 
 
 
 This platform is used to power internal IoT platform at O2 Czech Republic and is currently licensed with ASLv2.