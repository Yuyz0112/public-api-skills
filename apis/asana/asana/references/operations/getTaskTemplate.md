# GET /task_templates/{task_template_gid}

**Resource:** [Task templates](../resources/Task-templates.md)
**Get a task template**
**Operation ID:** `getTaskTemplate`

<b>Required scope: </b><code>task_templates:read</code>

Returns the complete task template record for a single task template.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved requested task template |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: task_templates:read
