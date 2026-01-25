# GET /project_templates

**Resource:** [Project templates](../resources/Project-templates.md)
**Get multiple project templates**
**Operation ID:** `getProjectTemplates`

<b>Required scope: </b><code>project_templates:read</code>

Returns the compact project template records for all project templates in the given team or workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested team's or workspace's project templates. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: project_templates:read
