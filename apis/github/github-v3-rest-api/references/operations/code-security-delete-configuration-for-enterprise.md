# DELETE /enterprises/{enterprise}/code-security/configurations/{configuration_id}

**Resource:** [code-security](../resources/code-security.md)
**Delete a code security configuration for an enterprise**
**Operation ID:** `code-security/delete-configuration-for-enterprise`

Deletes a code security configuration from an enterprise.
Repositories attached to the configuration will retain their settings but will no longer be associated with
the configuration.

The authenticated user must be an administrator for the enterprise to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

