---
title: "Modernize APIs to run serverless using Apache CXF"
slug: modernize-apis-to-run-serverless-using-apache-cxf
speakers:
 - Dennis Kieselhorst
time_start: 2024-06-03 16:50:00
time_end: 2024-06-03 17:20:00
tracks:
 - API & Microservices
---

Years ago the Service-oriented architecture (SOA) architectural style came along with implementations of web services based on standards like the Web Service Description Language (WSDL) and SOAP. Many of these interfaces are still in place as of today as a change requires both provider and all consumers to agree on a new definition and change the implementation (often without any business value). The underlying infrastructure, sometimes based on Enterprise Services Buses (ESB) is however often end-of-life and hard to maintain.
 
 
 
 In this session you will learn how to modernize API infrastructure without changing the interface definition in the first place. Apache CXF allows to provide APIs using SOAP or RESTful HTTP protocol in a contract-first manner. The combination with cloud-based serverless function services like AWS Lambda enables you to reduce the management effort and lowering the cost by only paying for what you use.