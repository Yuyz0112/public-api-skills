# GET /workspaces/{workspace_gid}/custom_fields

**Resource:** [Custom fields](../resources/Custom-fields.md)
**Get a workspace's custom fields**
**Operation ID:** `getCustomFieldsForWorkspace`

<b>Required scope: </b><code>custom_fields:read</code>

Returns a list of the compact representation of all of the custom fields in a workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved all custom fields for the given workspace. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: custom_fields:read
