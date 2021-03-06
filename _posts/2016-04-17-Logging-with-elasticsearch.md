---
layout: post
title: Logging with Elastic search
date: '2016-04-17'
tags: programming
---

Demo on using ELK stack for logging and analysis. Included Vagrant box and install scripts for elasticsearch, logstash, kibana on ubuntu vm.

## ELK stack

ELK stack provides a complete solution for log collection and analysis.

 - Elasticsearch - the search engine
 - Logstash - the log collector
 - Kibana - the visualization tool

![placeholder](/public/file-logstash-es-kibana.png "ELK stack")

## The box

I've set up a vagrant box with ELK stack on it for a demo. Follow the links at the end of the article.
What is included:

- Vagrant file to set up an ubuntu 14.04 VM and install ELK components
- Bash scripts to install java 8, logstash 2.1, kibana 4.4, elasticsearch 2.3
- A logstash configuration, kibana dashboards, elastic template
- Some sample logs

Happy logging ...

## Links

- prezi [link](https://prezi.com/gbouaz-gj8g0/log-processing-and-analysis/)
- github [link](https://github.com/adam-gligor/archeology/tree/master/elkstack-demo-master/elkstack-demo-master)
- elastic home [link](https://www.elastic.co/)
