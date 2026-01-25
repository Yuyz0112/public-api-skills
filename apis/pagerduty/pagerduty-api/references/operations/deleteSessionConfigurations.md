# DELETE /session_configurations

**Resource:** [Session Configurations](../resources/Session-Configurations.md)
**Delete an account's session configurations.**
**Operation ID:** `deleteSessionConfigurations`

<!-- theme: warning -->
> ### Early Access
 
> This endpoint is in Early Access and may change at any time. You must pass in the X-EARLY-ACCESS header with the value of `session-configurations-early-access` to access it.

Deletes the session configurations for a PagerDuty account that was previously set.
The type parameter is required and specifies which configurations to delete.
A single type ('mobile' or 'web') or comma-separated list may be passed in.

Scoped OAuth requires: `session_configurations.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | Session Configurations deleted successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

