# GET /repos/{owner}/{repo}/code-security-configuration

**Resource:** [code-security](../resources/code-security.md)
**Get the code security configuration associated with a repository**
**Operation ID:** `code-security/get-configuration-for-repository`

Get the code security configuration that manages a repository's code security settings.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 204 | (reference) |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[code-security-configuration-for-repository](../schemas/code-security-configuration-for-repository/code-security-configuration-for-repository.md)

