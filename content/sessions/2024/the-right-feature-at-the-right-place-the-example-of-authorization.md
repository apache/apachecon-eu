---
title: "The right feature at the right place: the example of authorization"
slug: the-right-feature-at-the-right-place-the-example-of-authorization
speakers:
 - Nicolas Fränkel
time_start: 2024-06-03 16:10:00
time_end: 2024-06-03 16:40:00
track: API & Microservices
day: 1
timeslot: 13
room: Mirror Lounge

---

All mature tech stacks nowadays offer infrastructure-related capabilities, either a standard lib or in 3rd-party libraries, e.g., rate-limiting and authorization. While it's great to have such features, it's impossible to audit them easily. You'd need to be familiar with the stack and dive deep into the code. This approach just doesn't scale,
 
A well-designed system keeps the right feature at the right place. In this talk, I'll go through all steps toward making your system more easily auditable. I'll use the authorization of a security policy as an example and start from a regular Spring Boot project with Spring Security. I'll then move step-by-step, introducing the Open Policy Agent (OPA) and the Apache APISIX API Gateway.
 
The end result will have moved all authorization details buried in the code in a readable accessible place.