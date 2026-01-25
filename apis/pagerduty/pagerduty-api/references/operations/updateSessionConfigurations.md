# PUT /session_configurations

**Resource:** [Session Configurations](../resources/Session-Configurations.md)
**Configure an account's session configurations**
**Operation ID:** `updateSessionConfigurations`

<!-- theme: warning -->
> ### Early Access

> This endpoint is in Early Access and may change at any time. You must pass in the X-EARLY-ACCESS header with the value of `session-configurations-early-access` to access it.

Creates or updates session configurations for a PagerDuty Account. The configurations will take effect immediately for new sessions, while existing sessions for the specified `types` are immediately revoked.

Scoped OAuth requires: `session_configurations.write`


## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Session Configurations updated successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

