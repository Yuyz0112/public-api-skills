# PUT /orgs/{org}/actions/permissions/artifact-and-log-retention

**Resource:** [actions](../resources/actions.md)
**Set artifact and log retention settings for an organization**
**Operation ID:** `actions/set-artifact-and-log-retention-settings-organization`

Sets artifact and log retention settings for an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope or the "Actions policies" fine-grained permission to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-artifact-and-log-retention](../schemas/actions-artifact-and-log-retention/actions-artifact-and-log-retention.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | No content |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

