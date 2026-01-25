# GET /team.profile.get

**Resource:** [team.profile](../resources/team-profile.md)
**Operation ID:** `team_profile_get`

Retrieve a team's profile.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `users.profile:read` |
| `visibility` | query | string | No | Filter by visibility. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: users.profile:read
