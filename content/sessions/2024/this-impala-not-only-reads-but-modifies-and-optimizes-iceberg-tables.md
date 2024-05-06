---
title: "This Impala not only reads, but modifies and optimizes Iceberg tables"
slug: this-impala-not-only-reads-but-modifies-and-optimizes-iceberg-tables
speakers:
 - Zoltan Borok-Nagy
 - Péter Rózsa
 - Noémi Pap-Takács
time_start: 2024-06-03 16:50:00
time_end: 2024-06-03 17:20:00
track: Big Data Storage
day: 1
timeslot: 14
room: Rhapsody
---

Apache Impala is a distributed, massively parallel query engine for big data. Initially, it focused on fast query execution on top of large datasets that were ingested via long-running batch jobs. The table schema and the ingested data typically remained unchanged, and row-level modifications were impractical to say the least.
 
 
 
Today's expectations for modern data warehouse engines have risen significantly. Users now want to have RDBMS-like capabilities in their data warehouses. E.g., they often need to comply with regulations like GDPR or CCPA, i.e. they need to be able to remove or update records belonging to certain individuals.
 
 
 
 Apache Iceberg is a cutting-edge table format that delivers advanced write capabilities for large-scale data. It allows schema and partition evolution, time-travel, and the focus of this talk: row-level modifications and table maintenance features. Impala has had support for reading Iceberg tables and inserting data for a while, but the capability of deleting and updating rows only recently became available.
 
 
 
 Frequent modifications come with a cost: eventually, the table will become full of small data and so-called delete files. This degrades the performance of read operations over time. The new table maintenance statement in Impala, OPTIMIZE, merges small data files and eliminates delete files to keep our table healthy. To make partition-level maintenance easier, DROP PARTITION statement allows selective partition removal based on predicates.
 
 
 
 Join us for this session to discover how Apache Impala evolved to meet emerging requirements without compromising performance.