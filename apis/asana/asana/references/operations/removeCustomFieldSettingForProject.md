# POST /projects/{project_gid}/removeCustomFieldSetting

**Resource:** [Projects](../resources/Projects.md)
**Remove a custom field from a project**
**Operation ID:** `removeCustomFieldSettingForProject`

<b>Required scope: </b><code>projects:write</code>

Removes a custom field setting from a project.

## Request Body

Information about the custom field setting being removed.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the custom field from the project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write
