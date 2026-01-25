# POST /admin.teams.settings.setDefaultChannels

**Resource:** [admin.teams.settings](../resources/admin-teams-settings.md)
**Operation ID:** `admin_teams_settings_setDefaultChannels`

Set the default channels of a workspace.

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
