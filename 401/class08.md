# Reading: Access Control (ACL)

## When is Basic Authorization used vs. Bearer Authorization?
 
> The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret (see RFC7616 and RFC7617).
> The Bearer authentication scheme is dedicated to the authentication using a token and is described by the RFC6750.

 ![](https://i.stack.imgur.com/HQF1L.png)

 ## What does the JSON Web Token package do?
 > create token/signature .sign() of a SECRET and use algorthims to encrypt them and provide options to them and verify tokens and retrive thier pay load headers .verify using the SECRET.

## What considerations should we make when creating and storing a SECRET?

1. 1-store secret in the .env file and never show them to the public .
2. 2-use randomly generated and long secrets

## What is RBAC?

> RBAC is nothing more than the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs.

## Benefits of RBAC?

> With the proper implementation of RBAC, the assignment of access rights becomes systematic and repeatable. Further, it is much easier to audit user rights, and to correct any issues identified.

## RBAC implementation

1. Inventory your systems
2. Analyze your workforce and create roles
3. Assign people to roles
4. Never make one-off changes
5. Audit
