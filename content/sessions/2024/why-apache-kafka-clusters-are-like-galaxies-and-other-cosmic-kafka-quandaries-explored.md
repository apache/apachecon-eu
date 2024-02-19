---
title: "Why Apache Kafka Clusters Are Like Galaxies (And Other Cosmic Kafka Quandaries Explored)"
slug: why-apache-kafka-clusters-are-like-galaxies-and-other-cosmic-kafka-quandaries-explored
speakers:
 - Paul Brebner
time_start: 2024-06-05 14:00:00
time_end: 2024-06-05 14:30:00
tracks:
 - Performance Engineering
---

Instaclustr (now part of NetApp) manages 100s of Apache Kafka clusters of many different sizes, for a variety of use cases and customers. For the last 7 years I’ve been focused outwardly on exploring Kafka application development challenges, but recently I decided to look inward and see what I could discover about the performance, scalability and resource characteristics of the Kafka clusters themselves. Using a suite of Performance Engineering techniques, I will reveal some surprising discoveries about cosmic Kafka mysteries in our data centres, related to: cluster sizes and distribution (using Zipf’s Law), horizontal vs. vertical scalability, and predicting Kafka performance using metrics, modelling and regression techniques. These insights are relevant to Kafka developers and operators.