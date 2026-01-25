# POST /admin.users.setAdmin

**Resource:** [admin.users](../resources/admin-users.md)
**Operation ID:** `admin_users_setAdmin`

Set an existing guest, regular user, or owner to be an admin user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.users:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.users:write
