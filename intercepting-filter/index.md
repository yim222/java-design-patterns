---
layout: pattern
title: Intercepting Filter
folder: intercepting-filter
permalink: /patterns/intercepting-filter/
categories: Behavioral
tags: Java
---

**Intent:** Provide pluggable filters to conduct necessary pre-processing and
post-processing to requests from a client to a target
 
![alt text](./etc/intercepting-filter.png "Intercepting Filter")
 
**Applicability:** Use the Intercepting Filter pattern when

* a system uses pre-processing or post-processing requests
* a system should do the authentication/ authorization/ logging or tracking of request and then pass the requests to corresponding handlers 
* you want a modular approach to configuring pre-processing and post-processing schemes

**Real world examples:**

* [Struts 2 - Interceptors](https://struts.apache.org/docs/interceptors.html)

**Credits:**

* [TutorialsPoint - Intercepting Filter](http://www.tutorialspoint.com/design_pattern/intercepting_filter_pattern.htm)
* [Presentation Tier Patterns](http://www.javagyan.com/tutorials/corej2eepatterns/presentation-tier-patterns)
