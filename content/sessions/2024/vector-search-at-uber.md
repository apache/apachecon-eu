---
title: "Vector Search at Uber"
slug: vector-search-at-uber
speakers:
 - Yupeng Fu
time_start: 2024-06-03 14:00:00
time_end: 2024-06-03 14:30:00
track: Search
day: 1
timeslot: 9
room: Rhapsody
---

Vector Search has been regarded as a revolution for Search and Information Retrieval since the breakthrough with BERT and GPT in 2018. There has been an ever growing interest from both academia and industry in using machine learning models and vector search to leverage all sorts of content beyond the lexical features, including images, events, contextual semantics and so on. 
  
At Uber, we added the Vector Search support by leveraging Apache Lucene to our Search platform, and empower multiple business-critical use cases, such as Semantic Search and Gen AI support. In this talk, we'll walk through how we incorporated the KNN search capability over the cutting-edge HNSW algorithm from Lucene 9, and extended it with functionalities like ingesting live vector updates. And we will share our learnings and optimizations to scale the vector search solution up to meet Uber’s scalability requirements. Lastly, as an example, we'll highlight our collaboration with the Uber Maps team on enabling Geo-Semantics search, which significantly improved the search quality by vectorizing the semantic signals in the Maps search solution.