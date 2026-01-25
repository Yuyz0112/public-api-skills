# POST /dnd.setSnooze

**Resource:** [dnd](../resources/dnd.md)
**Operation ID:** `dnd_setSnooze`

Turns on Do Not Disturb mode for the current user, or changes its duration.

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: dnd:write
