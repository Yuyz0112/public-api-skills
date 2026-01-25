# POST /admin.emoji.remove

**Resource:** [admin.emoji](../resources/admin-emoji.md)
**Operation ID:** `admin_emoji_remove`

Remove an emoji across an Enterprise Grid organization

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:write
