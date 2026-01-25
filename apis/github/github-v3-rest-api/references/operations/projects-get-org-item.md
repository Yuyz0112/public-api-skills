# GET /orgs/{org}/projectsV2/{project_number}/items/{item_id}

**Resource:** [projects](../resources/projects.md)
**Get an item for an organization owned project**
**Operation ID:** `projects/get-org-item`

Get a specific item from an organization-owned project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fields` | query | any | No | Limit results to specific fields, by their IDs. If not specified, the title field will be returned.

Example: fields[]=123&fields[]=456&fields[]=789 or fields=123,456,789 |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[projects-v2-item-with-content](../schemas/projects-v2-item-with-content/projects-v2-item-with-content.md)

