---
title: "Moving Apache Cassandra command execution and monitoring from JMX to CQL: A Developer's Overview"
slug: moving-apache-cassandra-command-execution-and-monitoring-from-jmx-to-cql-a-developer-s-overview
speakers:
 - Maxim Muzafarov
time_start: 2024-06-03 11:10:00
time_end: 2024-06-03 11:40:00
track: Cassandra
day: 1
timeslot: 5
room: Symphony
---

Monitoring and management go hand in hand in distributed storage systems, and this is true for Apache Cassandra as well. Apache Cassandra has a wide range of monitoring and management API extensions that provide insight into its internal processes and make management operations accessible.
  
This talk will provide an overview of several new initiatives that are closely related from a software developer's perspective. These initiatives follow the same design principles and their overall direction can be characterized as a strategic shift in both management and monitoring from JMX to CQL. They aim to simplify the execution of management commands and monitoring operations for Apache Cassandra, while addressing API inconsistencies and operational complexity challenges by attempting to harmonize different APIs such as JMX, Virtual Tables, and REST. This unified approach emphasizes a close relationship between monitoring and management, leveraging concepts to create a more efficient, secure, and user-friendly platform for operators and developers.