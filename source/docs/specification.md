---
title: Specification
description: Specification for Resk
extends: _layouts.documentation
section: content
---

# Specification

Resk as a push server needs to define some formal specification...

-[x] Redis - <https://redis.io/topics/protocol>  
-[x] Kafka - <https://cwiki.apache.org/confluence/display/KAFKA/KIP-595%3A+A+Raft+Protocol+for+the+Metadata+Quorum>  

## Authentication

Define the authentication and authorization. Users should be able to plug in their own authentication
such as `Oauth2` and `Openid-Connect`

- Open Distro <https://github.com/opendistro-for-elasticsearch/security>

## Pluggable

Define the pluggable bits - Let's use `OSGi`

## Web Push

-- TODO WebPush

## Android Push

## APNS (Apple)

## Configuration Reference

Define a formal specification for all configuration values