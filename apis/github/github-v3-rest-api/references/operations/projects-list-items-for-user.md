# GET /users/{username}/projectsV2/{project_number}/items

**Resource:** [projects](../resources/projects.md)
**List items for a user owned project**
**Operation ID:** `projects/list-items-for-user`

List all items for a specific user-owned project accessible by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `q` | query | string | No | Search query to filter items, see [Filtering projects](https://docs.github.com/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/filtering-projects) for more information. |
| `fields` | query | any | No | Limit results to specific fields, by their IDs. If not specified, the title field will be returned.

Example: `fields[]=123&fields[]=456&fields[]=789` or `fields=123,456,789` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [projects-v2-item-with-content](../schemas/projects-v2-item-with-content/projects-v2-item-with-content.md)

