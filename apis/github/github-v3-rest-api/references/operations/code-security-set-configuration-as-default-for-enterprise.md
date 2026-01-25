# PUT /enterprises/{enterprise}/code-security/configurations/{configuration_id}/defaults

**Resource:** [code-security](../resources/code-security.md)
**Set a code security configuration as a default for an enterprise**
**Operation ID:** `code-security/set-configuration-as-default-for-enterprise`

Sets a code security configuration as a default to be applied to new repositories in your enterprise.

This configuration will be applied by default to the matching repository type when created, but only for organizations within the enterprise that do not already have a default code security configuration set.

The authenticated user must be an administrator for the enterprise to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Default successfully changed. |
| 403 | (reference) |
| 404 | (reference) |

