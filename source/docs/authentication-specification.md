---
title: Authentication and Authorization Specification
description: Security via Authentication and Authorization
extends: _layouts.documentation
section: content
---

# Authentication and Authorization

When authentication and authorization is enabled, users will be required to provide valid credentials for
each data access. After authentication is successfull, authorization is performed, and the result of this
determines the access.

Authentication is decoupled from the `server` subsystem and can be plugged into either

- REST API - Cam use `native`, `file` or `AP`
- CLI      - Can use either `native` or `file` for authentication

## Authentication

Users should be able to authenticate via an `Authentication Provider`.

Authentication shall be delegated to one or more `Authentication Providers (AP)`. User information shall be
stored `natively`, on `file` or via a configured `AP` (e.g. AD, LDAP, OIDC).

### Authentication Provider

SPI to define authentication, roles mapping etc

## Authorization

Users shall be assigned roles, and these roles define the permissions assigned to it. There will be built in
roles, and users will be able to create additional if they have the permission.

Permissions will be managed internally in the server

Define built-in permissions. Users should be able to create roles, ans assign permissions to roles
Define built-in roles


## Authentication Providers

Define an SPI for authentication providers

-[x] Openid  
-[x] LDAP  
-[x] Active Directory  
-[x] Kerberos
