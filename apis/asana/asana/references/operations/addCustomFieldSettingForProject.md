# POST /projects/{project_gid}/addCustomFieldSetting

**Resource:** [Projects](../resources/Projects.md)
**Add a custom field to a project**
**Operation ID:** `addCustomFieldSettingForProject`

<b>Required scope: </b><code>projects:write</code>

Custom fields are associated with projects by way of custom field settings.  This method creates a setting for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

Information about the custom field setting.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully added the custom field to the project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write
