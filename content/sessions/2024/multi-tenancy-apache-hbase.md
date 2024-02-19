---
title: "Multi Tenancy — Apache Hbase"
slug: multi-tenancy-apache-hbase
speakers:
 - Mallikarjun Venkataswamyreddy
time_start: 2024-06-04 11:10:00
time_end: 2024-06-04 11:40:00
tracks:
 - Big Data Storage
---

Apache HBase is an open-source non-relational distributed database with multiple components such as Zookeeper, JournalNodes, Hmaster, Namenodes, Datanodes, Regionserver. Managing independent clusters for each use case is operationally heavy and sub-optimal utilization of hardware. Hence there is a need for providing a consolidated, managed, multi-tenant HBase cluster with stronger isolation guarantees in many organizations.
 
 
 
 In this talk, we are going to talk about how we approached this problem, made tradeoffs and run large scale multi-tenant hbase clusters with strict isolation guarantees.
 
 
 
 Blog Links:
 
 Part I: https://blog.flipkart.tech/hbase-multi-tenancy-part-i-37cad340c0fa
 
 Part II: https://blog.flipkart.tech/hbase-multi-tenancy-part-ii-79488c19b03d