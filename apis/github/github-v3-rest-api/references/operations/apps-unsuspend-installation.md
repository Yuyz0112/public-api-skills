# DELETE /app/installations/{installation_id}/suspended

**Resource:** [apps](../resources/apps.md)
**Unsuspend an app installation**
**Operation ID:** `apps/unsuspend-installation`

Removes a GitHub App installation suspension.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |

