---
title: "Building a Kubernetes Operator for Apache Flink in Java"
slug: building-a-kubernetes-operator-for-apache-flink-in-java
speakers:
 - Gyula Fora
 - Attila Mészáros
time_start: 2024-06-05 12:30:00
time_end: 2024-06-05 13:00:00
track: Data Engineering
day: 3
timeslot: 7
room: Rhapsody
---

Managing complex applications such as data processing systems on Kubernetes is a formidable challenge even for the most seasoned engineers. Whether you want to build applications that operate themselves or provision infrastructure from Java code, Kubernetes Operators are the way to go.
 
The Java Operator SDK is a production-ready framework that makes implementing Kubernetes Operators in Java easy. We will give you a run-down on the basics of operators and implementing one from scratch in Java and why this library may be the right choice for your project.
 
Once you know the basics of Kubernetes operators, we will show you how we used the JOSDK to build the official Apache Flink Kubernetes Operator in Java. We highlight the key differentiating factors compared to other Go based operator frameworks that made this library successful in large scale production use-cases.