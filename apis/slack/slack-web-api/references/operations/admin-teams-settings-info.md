# GET /admin.teams.settings.info

**Resource:** [admin.teams.settings](../resources/admin-teams-settings.md)
**Operation ID:** `admin_teams_settings_info`

Fetch information about settings in a workspace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.teams:read` |
| `team_id` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:read
