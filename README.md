# Documentation
This is the project's wiki and documentation

The goal of the project is to provide a small flexible technology stack for the web that
avoids monolithic architecture due to structured interfaces and a single cross language, cross platform protocol.

## Properties the stack should have:

* vendor neutral - MIT or Apache 2 licencing
* light weight - HTML5 CSS3, ECMAscript, Thrift protocol
* request reply and publish subscribe - http and websockets
* high performance - Thrift protocol, tcp/ip (websockets)
* cross language - Thrift protocol
* automatic language stub generation -Thrift compiler
* language agnostic network - Thrift protocol
* modular polyglot microservices - PHP, Java, Javascript, PERL, C#, C++
* evolving interfaces without breaking existing implementations -Thrift protocol
* explicit and centralized interface and bounded context design -Thrift IDL

## Problem domains to solve:

* Database caching
* Key value store for cross language state caching
* Datagrid, distributed key value store supporting ACID
* Web session clustering, maybe cross language?
* Cross language protocol - Thrift TCompact binary protocol

## Resources:

https://dzone.com/articles/linking-apache-ignite-and-apache-kafka-for-highly

https://en.m.wikipedia.org/wiki/List_of_in-memory_databases

Wider den Monolith - Am Ende wird alles gut: https://vimeo.com/114853516

https://dzone.com/articles/polyglot-microservices-and-apache-thrift
