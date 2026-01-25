# GET /rest/api/3/universal_avatar/view/type/{type}

**Resource:** [Avatars](../resources/Avatars.md)
**Get avatar image by type**
**Operation ID:** `getAvatarImageByType`

Returns the default project, issue type or priority avatar image.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | path | enum: issuetype, project, priority | Yes | The icon type of the avatar. |
| `size` | query | enum: xsmall, small, medium... | No | The size of the avatar image. If not provided the default size is returned. |
| `format` | query | enum: png, svg | No | The format to return the avatar image in. If not provided the original content format is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if an avatar is not found or an avatar matching the requested size is not found. |

**Success Response Schema:**

[StreamingResponseBody](../schemas/Streaming/StreamingResponseBody.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
