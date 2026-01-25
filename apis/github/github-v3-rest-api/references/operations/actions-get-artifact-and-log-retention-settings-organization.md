# GET /orgs/{org}/actions/permissions/artifact-and-log-retention

**Resource:** [actions](../resources/actions.md)
**Get artifact and log retention settings for an organization**
**Operation ID:** `actions/get-artifact-and-log-retention-settings-organization`

Gets artifact and log retention settings for an organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope or the "Actions policies" fine-grained permission to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-artifact-and-log-retention-response](../schemas/actions-artifact-and-log-retention-response/actions-artifact-and-log-retention-response.md)

