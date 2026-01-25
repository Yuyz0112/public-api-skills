# GET /rest/api/3/avatar/{type}/system

**Resource:** [Avatars](../resources/Avatars.md)
**Get system avatars by type**
**Operation ID:** `getAllSystemAvatars`

Returns a list of system avatar details by owner type, where the owner types are issue type, project, user or priority.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | path | enum: issuetype, project, user... | Yes | The avatar type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 500 | Returned if an error occurs while retrieving the list of avatars. |

**Success Response Schema:**

[SystemAvatars](../schemas/System/SystemAvatars.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
