---
title: "Data enrichment patterns with Apache Flink"
slug: data-enrichment-patterns-with-apache-flink
speakers:
 - Subham Rakshit
time_start: 2024-06-05 11:50:00
time_end: 2024-06-05 12:20:00
tracks:
 - Data Engineering
---

Data enrichment is a critical step in stream processing. Real-time enrichment of streaming data with contextual information adds missing information, improves accuracy, increases trustworthiness, and facilitates better decision-making. Contextual data can be static or dynamic and obtained in various ways - APIs, databases, files and even as a stream. While there are multiple design patterns to perform data enrichment, it is not always obvious when one pattern is preferred over the other.
 
 
 
 In this session we will show common enrichment patterns for streaming data, and how to implement them using Apache Flink. We will cover patterns in scenarios where reference data is static, available through external APIs, or available as a change data stream. We will dive into internal details about Flink state and how it stores reference data.
 
 
 
 You will walk away with clear understanding of how to use these patterns in your architecture. You can make an informed decision about how stream data enrichment can meet the throughput and latency goals of your use case.