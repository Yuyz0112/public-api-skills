# GET /task_templates

**Resource:** [Task templates](../resources/Task-templates.md)
**Get multiple task templates**
**Operation ID:** `getTaskTemplates`

<b>Required scope: </b><code>task_templates:read</code>

Returns the compact task template records for some filtered set of task templates. You must specify a `project`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `project` | query | string | No | The project to filter task templates on. |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved requested task templates |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: task_templates:read
