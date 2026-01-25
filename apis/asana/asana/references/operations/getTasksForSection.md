# GET /sections/{section_gid}/tasks

**Resource:** [Tasks](../resources/Tasks.md)
**Get tasks from a section**
**Operation ID:** `getTasksForSection`

<b>Required scope: </b><code>tasks:read</code>

*Board view only*: Returns the compact section records for all tasks within the given section.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the section's tasks. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
