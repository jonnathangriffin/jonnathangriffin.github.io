---
title: 'Pentesting Black Hat'
subtitle: 'update once and done'
date: 2020-03-30 00:00:00
description: Step by step for implementing automatic security updates for ubuntu.
---

## Authentication and SSO

- Brute Force
- SQL Injection `' OR 1=1 --`
- WeakPredictable Session ID


Security design principle 

Bypassing 2 factor auth
- brute force
- less used interfaces )might not be used on mobile)
- forced browsing - after logging in force browse to another page
- predictable reusable tokens

Modern Authetnication and Authorization Methods
- JSON Web Tokens jwt.io
  - Weak secret key
- SAML
  - signature is not validated
  - XML cononicalization by adding a comment by the user id
- OAuth

Brute force a jwt token
1. Capture a valid jwt token and decode it with jwt.io


## Password reset attacks
- reset link
- OTP

Cookie swap attack
Password reset tokens do not expire
Unicode attacks

## Business Logic Flaws

