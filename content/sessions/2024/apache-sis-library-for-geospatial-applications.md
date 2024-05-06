---
title: "Apache SIS library for geospatial applications"
slug: apache-sis-library-for-geospatial-applications
speakers:
 - Martin Desruisseaux
time_start: 2024-06-04 14:40:00
time_end: 2024-06-04 15:10:00
track: Data Engineering
day: 2
timeslot: 10
room: Rhapsody
---

Geospatial data are ubiquitous, but the difficulty of handling them accurately is often under-estimated. Various projects implement their own routines for performing geospatial operations, but not always with awareness about the pitfalls of simple approaches. This talk will present some of the difficulties in mapping "real world" to digital data. Then we will present some international standards published jointly by the Open Geospatial Consortium (OGC) and the International Organization for Standardization (ISO). Those standards not only improve interoperability, but also provides insights from the experts who designed them. Then we will present Apache SIS, a Java library following closely a dozen of OGC/ISO standards for helping developers to create their own geospatial application. This presentation will do a quick overview of the following standards, together with entry points in the Java API:
 
 
 
 • ISO 19115 — Metadata, for answering “what, where, when”.
 
 • ISO 19157 — Data Quality, for answering “how reliable”.
 
 • ISO 19111 — Referencing by coordinates, which includes map projections.
 
 • ISO 19112 — Geographic identifiers, including GeoHash and Military Grid Reference System.
 
 • ISO 19162 — Well-Known Text representation of coordinate reference systems.
 
 • ISO 19136 — Geography Markup Language (reference systems part only).
 
 • ISO 19143 — Filter encoding, for specifying a subset of resources.
 
 • ISO 19109 — Rules for application schema (i.e. “Features”).
 
 • OGC 19-008 — GeoTIFF format, for raster data.
 
 • GeoAPI 3.0.2 — Java interfaces derived from OGC/ISO abstract models.
 
 
 
 A value of Apache SIS is the integration between referencing, metadata and raster services among others. This integration, together with Apache SIS capability to handle advanced scenarios, will be demonstrated by a results of OGC Testbed-19 — Geospatial in space — in which SIS was used as a prototype. Finally, a JavaFX application will be shown for visualizing some of those functionalities.