# PUT /repos/{owner}/{repo}/actions/permissions/artifact-and-log-retention

**Resource:** [actions](../resources/actions.md)
**Set artifact and log retention settings for a repository**
**Operation ID:** `actions/set-artifact-and-log-retention-settings-repository`

Sets artifact and log retention settings for a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-artifact-and-log-retention](../schemas/actions-artifact-and-log-retention/actions-artifact-and-log-retention.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Empty response for successful settings update |
| 404 | (reference) |
| 422 | (reference) |

