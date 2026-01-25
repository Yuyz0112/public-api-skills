# GET /apps.permissions.scopes.list

**Resource:** [apps.permissions.scopes](../resources/apps-permissions-scopes.md)
**Operation ID:** `apps_permissions_scopes_list`

Returns list of scopes this app has on a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `none` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical successful paginated response |
| default | Typical error response |

## Security

- **slackAuth**: none
