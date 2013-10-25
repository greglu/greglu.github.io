---
layout: post
title:  "Crash Course Into Open Source Monitoring - Part 1"
date:   2013-10-17 14:45:00
categories: monitoring open-source
---

This write-up is meant as a starting point into systems and application monitoring for developers and DevOps engineers alike. There's a wealth of tools and resources on the internet, but getting a big picture view of how everything fits together is harder to understand when you begin diving into this topic.

If you suddenly find yourself as a new DevOps engineer, or a developer needing to do operations work on your software, then hopefully this guide can serve as a starting point into the world of open source monitoring.


# Open Source Tool List

There are lots of open source tools out there for monitoring, and I'll begin by separating them into these loosely defined categories, then attempt to explain the underlying problems each category addresses. This list is in no way comprehensive, but represent tools which I have tried out myself. Keep in mind that many of these could be configured in such a way that would cause it to fall into another category.

## Metrics
* Graphite: <http://graphite.wikidot.com/>
* StatsD: <https://github.com/etsy/statsd/>
* collectd: <http://collectd.org/>
* Diamond: <https://github.com/BrightcoveOS/Diamond>
* OpenTSDB: <http://opentsdb.net/>
* Yammer Metrics: <http://metrics.codahale.com/>

## Centralized Logging
* Logstash: <http://logstash.net/>
* Graylog2: <http://graylog2.org/>
* Syslog-ng: <http://www.balabit.com/network-security/syslog-ng>

## General Purpose Monitoring/Alerting Platforms
* Zabbix: <http://www.zabbix.com/>
* Nagios: <http://www.nagios.org/>
* Cacti: <http://www.cacti.net/>

## Cluster Monitoring
* Ganglia: <http://ganglia.sourceforge.net/>

## Event Steam Processing
* Riemann: <http://riemann.io/>


# Reading this Guide

This guide is broken up into more detailed write-ups:

* [Crash Course Into Open Source Monitoring - Part 2 (Metrics)]({% post_url 2013-10-18-crash-course-into-open-source-monitoring-2 %})
* [Crash Course Into Open Source Monitoring - Part 3 (Centralized Logging)]({% post_url 2013-10-19-crash-course-into-open-source-monitoring-3 %})
* [Crash Course Into Open Source Monitoring - Part 4 (Logstash)]({% post_url 2013-10-23-crash-course-into-open-source-monitoring-4 %})


# Resources

* <http://www.quora.com/What-is-the-best-server-monitoring-software-to-use>
* <http://en.wikipedia.org/wiki/Comparison_of_network_monitoring_systems>
* <http://codeascraft.com/category/infrastructure/>
* <http://dashboarddude.com/blog/2013/01/23/dashboards-for-graphite/>
* <http://codeascraft.com/2011/02/15/measure-anything-measure-everything/>
* <http://edgeofsanity.net/article/2012/07/09/silly-graphite-trick.html>
