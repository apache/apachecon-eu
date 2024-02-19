---
title: "Efficient, Low Latency Ingestion to Large Tables via Apache Flink and Apache Iceberg"
slug: efficient-low-latency-ingestion-to-large-tables-via-apache-flink-and-apache-iceberg
speakers:
 - Marton Balassi
 - Peter Vary
time_start: 2024-06-05 11:10:00
time_end: 2024-06-05 11:40:00
tracks:
 - Performance Engineering
---

One of the primary challenges of data ingestion is the tradeoff between the latency of data availability for the downstream systems and the extent to which data is optimised for efficient reading. When ingesting continuous incoming data streams with low latency, Apache Flink is a data processing engine that shines. Apache Iceberg is one of the most popular table formats for large tables. To get the best of both worlds, and continuously ingest data and see near real-time changes to tables queried by various engines, tight integration is needed between these two Apache projects.
 
 
 
 Basic integration has been available in open source for a long time, but when processing high volume data, the performance becomes crucial. Near real-time read from Iceberg tables needs frequent commits, and each commit creates a new set of files. On the other hand, reading from Iceberg tables is more optimal when the number of files are smaller. There are several ongoing projects to balance these needs and keep the number of files small. Balanced writes helps when the number of partitions are comparable to the parallelization level. Performing periodic compaction helps when the write throughput is more important and additional resources could be used to rewrite the data in a more optimal format.
 
 
 
 Development of these new features required changes in both the Apache Flink and the Apache Iceberg code base. In our talk discuss we the planning process coordinating two Apache communities, the implementation and the synchronization between projects. We compare our approach with alternative solutions like Apache Hudi and Apache Paimon, highlight the pros and cons of the different solutions, and showcase the possibilities in a brief demo.