---
title: "Cassandra CIDR filtering authorizer (CEP-33)"
slug: cassandra-cidr-filtering-authorizer-cep-33
speakers:
 - Shailaja Koppu
time_start: 2024-06-03 14:00:00
time_end: 2024-06-03 14:30:00
track: Cassandra
day: 1
timeslot: 9
room: Symphony
---

As Cassandra clusters and users onboarding to multi cloud platforms, users may access Cassandra clusters from on-premise and from various cloud platforms. Admins may need to restrict certain users/teams to access from certain IP ranges, aka, CIDR groups. Also, may need to restrict superusers credentials usage from third party clouds. 
 
 
 
 CIDR filtering authorizer provides capability for admins to configure allow or disallow users access from different CIDR groups, which can help in preventing misuse of copied or hacked credentials. Please see CEP-33 https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-33:+CIDR+filtering+authorizer for further details.