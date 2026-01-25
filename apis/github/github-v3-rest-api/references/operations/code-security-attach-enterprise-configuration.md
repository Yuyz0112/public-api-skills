# POST /enterprises/{enterprise}/code-security/configurations/{configuration_id}/attach

**Resource:** [code-security](../resources/code-security.md)
**Attach an enterprise configuration to repositories**
**Operation ID:** `code-security/attach-enterprise-configuration`

Attaches an enterprise code security configuration to repositories. If the repositories specified are already attached to a configuration, they will be re-attached to the provided configuration.

If insufficient GHAS licenses are available to attach the configuration to a repository, only free features will be enabled.

The authenticated user must be an administrator for the enterprise to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

