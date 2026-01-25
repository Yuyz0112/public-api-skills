# POST /admin.users.session.reset

**Resource:** [admin.users.session](../resources/admin-users-session.md)
**Operation ID:** `admin_users_session_reset`

Wipes all valid sessions on all devices for a given user

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
