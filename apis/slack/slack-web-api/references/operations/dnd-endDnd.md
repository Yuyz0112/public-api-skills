# POST /dnd.endDnd

**Resource:** [dnd](../resources/dnd.md)
**Operation ID:** `dnd_endDnd`

Ends the current user's Do Not Disturb session immediately.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `dnd:write` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: dnd:write
