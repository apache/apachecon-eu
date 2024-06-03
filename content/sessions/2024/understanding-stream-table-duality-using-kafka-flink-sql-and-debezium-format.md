---
title: "Understanding stream table duality using Kafka, Flink SQL and Debezium format"
slug: understanding-stream-table-duality-using-kafka-flink-sql-and-debezium-format
speakers:
 - Muhammet Orazov
time_start: 2024-06-05 16:00:00
time_end: 2024-06-05 16:30:00
track: Big Data Compute
day: 3
timeslot: 13
room: Rhapsody

---

Kafka Streams, ksqlDB or Flink SQL are popular processing engines that enable us to run SQL queries on top of streaming data. Isn't it fascinating that we can run SQL queries on top of streaming data as if they were relational tables, or convert a table into a stream of changelog events? This is known as the stream-table duality.
 
 
 
 In this talk we will try to understand how it works under the hood using Flink SQL, Kafka connector with Debezium JSON/Avro format.
 
 
 
 The following points will be presented and discussed:
 
 
 
 - What is stream-table duality?
 
 - Change data capture (CDC) event descriptions
 
 - SQL queries on top of changelog data
 
 - Short Demo
 
 - Conclusion and Q&A
 
 
 
 At the conclusion of the presentation, the attendees will possess a more comprehensive understanding of stream-table duality, how it works in practice, and how to apply it into their own systems.