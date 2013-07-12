---
layout: post
title:  "You should know about Dropwizard."
date:   2013-07-12 18:00:00
categories: frameworks
---

Spoiler alert! [Dropwizard](http://dropwizard.codahale.com) is awesome.

As succinctly put on the website, Dropwizard is a Java framework for 
developing ops-friendly, high-performance, RESTful web services. I can 
confirm that this is absolutely true.

I am a hardcore [Spring MVC](http://www.springsource.org/spring-framework)
geek. I've created RESTful services using Spring for quite some time, and 
despite the configuration lead time required (lessened with the recent 
addition of JavaConfig), I was quite happy.

When I stumbled upon Dropwizard, I was actually searching for ways to make
my Spring services more production ready and ops friendly, with better
logging, metrics and performance monitoring. What first struck me about
Dropwizard is how much of that comes out of the box. It helps that 
[Coda Hale](http://www.twitter.com/coda), creator of Dropwizard, is also
the brains behind [Metrics](http://metrics.codahale.com), the unparalleled
library for instrumenting your Java applications.

In addition to all the nice features that will make your ops folks love you,
Dropwizard is also powerful, yet lightweight. I've created dozens of services
with the framework, and there's been nothing it couldn't handle, and it
undoubtably cut development time in half.

I'll be diving into some nitty gritty Dropwizard examples in the future, 
but for now, do yourself a favour and check it out.