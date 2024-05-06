---
title: "Solr Eclipse - Zomato's Journey to 64 Million Search Queries a Day"
slug: solr-eclipse-zomato-s-journey-to-64-million-search-queries-a-day
speakers:
 - Angad Sharma
time_start: 2024-06-03 12:30:00
time_end: 2024-06-03 13:00:00
track: Search
day: 1
timeslot: 7
room: Rhapsody
---

Zomato is the Indian market leader for restaurant aggregation and food delivery.
 
This is a story of how Zomato leverages the power of Apache Solr at scale, some of the problems we faced and how we tackled them to reach where we are now.
 
Starting with just one Solr instance serving 1000 queries a day with 10K restaurants, to building and shipping a massive, first in class, search server with the capability of seamlessly searching 100 Million restaurant catalogues (SKUs), 800K+ restaurants and 50K+ unique dishes in 13 different languages at 64 Million search queries a day.
 
Moreover, how Zomato leverages Solr to power their entire homepage, serving 2 Million restaurants to customers at peak per second! 
 
This will be a thrilling ride about how we host our fault tolerant solr cluster setup, leveraging AWS, keeping a stellar balance between scalability, resiliency, and cost. Also about the struggles we overcame handling such a huge (50GB+) index size, search volume, faceting, filtering, aliasing, also about how we overcame issues like index explosion, full index corruption, slow indexing by leveraging the glorious community, using tools like profilers, remote debugging and much more!
 
If time permits, we will also get into how we used solr cloud to solve another use-case altogether, our journey, and the issues we faced at scale.