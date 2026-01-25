# POST /admin.apps.restrict

**Resource:** [admin.apps](../resources/admin-apps.md)
**Operation ID:** `admin_apps_restrict`

Restrict an app for installation on a workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.apps:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.apps:write
