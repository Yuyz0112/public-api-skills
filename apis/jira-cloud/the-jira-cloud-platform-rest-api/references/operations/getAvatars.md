# GET /rest/api/3/universal_avatar/type/{type}/owner/{entityId}

**Resource:** [Avatars](../resources/Avatars.md)
**Get avatars**
**Operation ID:** `getAvatars`

Returns the system and custom avatars for a project, issue type or priority.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  for custom project avatars, *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project the avatar belongs to.
 *  for custom issue type avatars, *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for at least one project the issue type is used in.
 *  for system avatars, none.
 *  for priority avatars, none.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | path | enum: project, issuetype, priority | Yes | The avatar type. |
| `entityId` | path | string | Yes | The ID of the item the avatar is associated with. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the avatar type is invalid, the associated item ID is missing, or the item is not found. |

**Success Response Schema:**

[Avatars](../schemas/Avatars/Avatars.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
