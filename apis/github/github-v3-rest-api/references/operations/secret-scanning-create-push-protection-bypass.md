# POST /repos/{owner}/{repo}/secret-scanning/push-protection-bypasses

**Resource:** [secret-scanning](../resources/secret-scanning.md)
**Create a push protection bypass**
**Operation ID:** `secret-scanning/create-push-protection-bypass`

Creates a bypass for a previously push protected secret.

The authenticated user must be the original author of the committed secret.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | User does not have enough permissions to perform this action. |
| 404 | Placeholder ID not found, or push protection is disabled on this repository. |
| 422 | Bad request, input data missing or incorrect. |
| 503 | (reference) |

**Success Response Schema:**

[secret-scanning-push-protection-bypass](../schemas/secret-scanning-push-protection-bypass/secret-scanning-push-protection-bypass.md)

