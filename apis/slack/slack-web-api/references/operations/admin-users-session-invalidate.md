# POST /admin.users.session.invalidate

**Resource:** [admin.users.session](../resources/admin-users-session.md)
**Operation ID:** `admin_users_session_invalidate`

Invalidate a single session for a user by session_id

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
