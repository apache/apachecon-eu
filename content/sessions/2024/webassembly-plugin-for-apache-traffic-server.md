---
title: "WebAssembly plugin for Apache Traffic Server"
slug: webassembly-plugin-for-apache-traffic-server
speakers:
 - Shu Kit Chan
time_start: 2024-06-05 12:30:00
time_end: 2024-06-05 13:00:00
tracks:
 - Tomcat, Httpd and other servers
---

The WebAssembly (Wasm) plugin for Apache Traffic Server (ATS) allows WebAssembly modules following the "proxy-wasm" specification to be run on ATS.
 
 
 
 The talk will begin by first introducing the background and history of plugins and programmability of ATS. I will go over the short comings of the current offerings and then introduce the Wasm plugin as an alternative solution for them. I will then talk about the "proxy-wasm" specification, which describes the support of WebAssembly modules for proxy server software. This has already been implemented by a few open source proxy server, such as Envoy, Nginx and MOSN. And it is now coming to ATS through this plugin.
 
 
 
 Next I will go over the structure and implementation of the Wasm plugin. I will also talk about the different WebAssembly runtimes that we support, such as Wasmtime, WAMR and WasmEdge. And I will then do some demo on how to write code in different programming languages and compile them into Wasm modules to be used by this plugin.
 
 
 
 The talk will be concluded by going through some limitations and future enhancements for the plugin, including new features and performance improvement. I will also talk about some interesting use cases (e.g. performing AI inference on ATS through the support of Wasi-NN extension of WebAssembly) that can be made possible with this plugin. 
 
 
 
 I have given this talk in Community over Code conference in October 2023 in Halifax. I would like to do this talk again in the Community over Code EU conference with new improvements and learnings since then and it would be great to share our journey into WebAssembly with the EU open source community and I hope to collect even more feedbacks about our works as well.