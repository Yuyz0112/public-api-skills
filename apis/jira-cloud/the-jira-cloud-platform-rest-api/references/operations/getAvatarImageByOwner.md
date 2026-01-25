# GET /rest/api/3/universal_avatar/view/type/{type}/owner/{entityId}

**Resource:** [Avatars](../resources/Avatars.md)
**Get avatar image by owner**
**Operation ID:** `getAvatarImageByOwner`

Returns the avatar image for a project, issue type or priority.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  For system avatars, none.
 *  For custom project avatars, *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project the avatar belongs to.
 *  For custom issue type avatars, *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for at least one project the issue type is used in.
 *  For priority avatars, none.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | path | enum: issuetype, project, priority | Yes | The icon type of the avatar. |
| `entityId` | path | string | Yes | The ID of the project or issue type the avatar belongs to. |
| `size` | query | enum: xsmall, small, medium... | No | The size of the avatar image. If not provided the default size is returned. |
| `format` | query | enum: png, svg | No | The format to return the avatar image in. If not provided the original content format is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if an avatar is not found or an avatar matching the requested size is not found. |

**Success Response Schema:**

[StreamingResponseBody](../schemas/Streaming/StreamingResponseBody.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
