# DELETE /orgs/{org}/code-security/configurations/{configuration_id}

**Resource:** [code-security](../resources/code-security.md)
**Delete a code security configuration**
**Operation ID:** `code-security/delete-configuration`

Deletes the desired code security configuration from an organization.
Repositories attached to the configuration will retain their settings but will no longer be associated with
the configuration.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

