---
title: "OpenSSL and QUIC using FFM"
slug: openssl-and-quic-using-ffm
speakers:
 - Remy Maucherat
 - Jean-frederic Clere
time_start: 2024-06-05 14:00:00
time_end: 2024-06-05 14:30:00
tracks:
 - Tomcat, Httpd and other servers
---

This session explores the use of the FFM API from Java 22 to leverage native library capabilities, in the context of Apache Tomcat. OpenSSL is here being used to provide support for TLS through the JSSE API, without the need to use the tomcat-native wrapper library. Exploratory design of QUIC and HTTP/3 support from OpenSSL 3.3+ is also discussed.