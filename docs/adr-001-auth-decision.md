# ADR 001 - Authentication Decision

## Status
Accepted

## Context
We require a secure and manageable way to authenticate students, proctors, and admins.

## Decision
Use Firebase Authentication for user identity management.

## Consequences
- Easy frontend integration
- Supports multi-factor auth and social login
- Vendor lock-in risk with Firebase
