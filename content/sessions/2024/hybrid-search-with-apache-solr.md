---
title: "Hybrid Search with Apache Solr"
slug: hybrid-search-with-apache-solr
speakers:
 - Alessandro Benedetti
time_start: 2024-06-03 11:50:00
time_end: 2024-06-03 12:20:00
track: Search
day: 1
timeslot: 6
room: Rhapsody
---

Vector-based search gained incredible popularity in the last few years: Large Language Models fine-tuned for sentence similarity proved to be quite effective in encoding text to vectors and representing some of the semantics of sentences in a numerical form. 
 
 These vectors can be used to run a K-nearest neighbour search and look for documents/paragraphs close to the query in a n-dimensional vector space, effectively mimicking a similarity search in the semantic space (Apache Solr KNN Query Parser). Although exciting, vector-based search nowadays still presents some limitations: 
 
 - it’s very difficult to explain - e.g. why is document A returned and why at position K? 
 
 - it doesn’t care about exact keyword matching (and users still rely on keyword searches a lot)
 
 
 
 To mitigate these problems, combining lexical (traditional keyword-based) search with neural (vector-based) search is possible.
 
 So, what does it mean to combine these two worlds?
 
 Join us as we explore various ways of running hybrid search in Apache Solr, including tricks, suggestions, pros/cons and future works on this exciting new search approach!