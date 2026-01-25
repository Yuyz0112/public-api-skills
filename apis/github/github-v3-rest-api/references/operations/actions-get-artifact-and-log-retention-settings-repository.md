# GET /repos/{owner}/{repo}/actions/permissions/artifact-and-log-retention

**Resource:** [actions](../resources/actions.md)
**Get artifact and log retention settings for a repository**
**Operation ID:** `actions/get-artifact-and-log-retention-settings-repository`

Gets artifact and log retention settings for a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[actions-artifact-and-log-retention-response](../schemas/actions-artifact-and-log-retention-response/actions-artifact-and-log-retention-response.md)

