# Authentication

This document describes the authentication methods supported by this API.

## basicAuth

**Type:** http

Basic HTTP authentication. Allowed headers-- Authorization: Basic <api_key> | Authorization: Basic <base64 hash of `api_key:`>

- **Scheme:** basic

## bearerAuth

**Type:** http

Bearer HTTP authentication. Allowed headers-- Authorization: Bearer <api_key>

- **Scheme:** bearer
- **Bearer Format:** auth-scheme

