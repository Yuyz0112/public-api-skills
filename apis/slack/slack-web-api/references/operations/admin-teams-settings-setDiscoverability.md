# POST /admin.teams.settings.setDiscoverability

**Resource:** [admin.teams.settings](../resources/admin-teams-settings.md)
**Operation ID:** `admin_teams_settings_setDiscoverability`

An API method that allows admins to set the discoverability of a given workspace

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.teams:write` |

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
