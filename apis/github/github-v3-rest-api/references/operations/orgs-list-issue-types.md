# GET /orgs/{org}/issue-types

**Resource:** [orgs](../resources/orgs.md)
**List issue types for an organization**
**Operation ID:** `orgs/list-issue-types`

Lists all issue types for an organization. OAuth app tokens and personal access tokens (classic) need the read:org scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [issue-type](../schemas/issue-type/issue-type.md)

