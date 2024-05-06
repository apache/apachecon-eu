---
title: "Obtain, Distribute and Use Temporary Credentials Automatically in Apache Spark and Apache Flink"
slug: obtain-distribute-and-use-temporary-credentials-automatically-in-apache-spark-and-apache-flink
speakers:
 - Gabor Somogyi
time_start: 2024-06-05 14:40:00
time_end: 2024-06-05 15:10:00
track: Big Data Compute
day: 3
timeslot: 10
room: Symphony

---

The importance of security is increasing sharply nowadays which must be reflected in open source projects. Apache Spark and Apache Flink are two of the most widely used Big Data frameworks which can be used for data processing. Both of them offer dozens of external service connectors where authentication plays an essential role. Each external system does its authentication in a different way but a common framework can be provided to ease the life of developers.
 
Introducing authentication creates many challenges for continuous data processing at high load. Credentials must be obtained in a timely and reliable manner which must be then propagated to several nodes. When too many nodes are authenticating at the same time then external services can be overloaded, which can cause temporary or permanent outages. A more reliable and less resource intensive solution was needed.
  
The mentioned problems have been addressed first in Apache Spark with a new delegation token framework which does all the heavy lifting. Building on the lessons learned in Spark a more generic implementation has been added to Apache Flink more recently. With these improvements workloads have been able to scale securely to thousands of workers. Attendees of this session will learn what are the common pitfalls of distributed system authentications and how to add such features easily to Apache Spark or Apache Flink.