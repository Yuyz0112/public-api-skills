# GET /repos/{owner}/{repo}/code-scanning/alerts/{alert_number}/instances

**Resource:** [code-scanning](../resources/code-scanning.md)
**List instances of a code scanning alert**
**Operation ID:** `code-scanning/list-alert-instances`

Lists all instances of the specified code scanning alert.

OAuth app tokens and personal access tokens (classic) need the `security_events` scope to use this endpoint with private or public repositories, or the `public_repo` scope to use this endpoint with only public repositories.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

Array of [code-scanning-alert-instance-list](../schemas/code-scanning-alert-instance-list/code-scanning-alert-instance-list.md)

