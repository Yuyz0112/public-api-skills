# GET /session_configurations

**Resource:** [Session Configurations](../resources/Session-Configurations.md)
**Get an account's session configurations**
**Operation ID:** `getSessionConfigurations`

<!-- theme: warning -->
> ### Early Access

> This endpoint is in Early Access and may change at any time. You must pass in the X-EARLY-ACCESS header with the value of `session-configurations-early-access` to access it.

Retrieves session configurations for a PagerDuty account. Returns an array containing
the requested configurations. If a specific type is requested, the array contains one item.
If no type is specified, the array contains all available configurations (mobile and web).
If no configurations exist, a 404 Not Found error will be returned.

A Session Configuration needs to be created before it can be retrieved and used.

Scoped OAuth requires: `session_configurations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | Session Configurations retrieved successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

