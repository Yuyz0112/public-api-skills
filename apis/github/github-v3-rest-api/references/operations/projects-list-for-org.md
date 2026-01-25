# GET /orgs/{org}/projectsV2

**Resource:** [projects](../resources/projects.md)
**List projects for organization**
**Operation ID:** `projects/list-for-org`

List all projects owned by a specific organization accessible by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `q` | query | string | No | Limit results to projects of the specified type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [projects-v2](../schemas/projects-v2/projects-v2.md)

