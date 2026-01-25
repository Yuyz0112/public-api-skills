# DELETE /rest/api/3/universal_avatar/type/{type}/owner/{owningObjectId}/avatar/{id}

**Resource:** [Avatars](../resources/Avatars.md)
**Delete avatar**
**Operation ID:** `deleteAvatar`

Deletes an avatar from a project, issue type or priority.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | path | enum: project, issuetype, priority | Yes | The avatar type. |
| `owningObjectId` | path | string | Yes | The ID of the item the avatar is associated with. |
| `id` | path | integer (int64) | Yes | The ID of the avatar. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the user does not have permission to delete the avatar, the avatar is not deletable. |
| 404 | Returned if the avatar type, associated item ID, or avatar ID is invalid. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
