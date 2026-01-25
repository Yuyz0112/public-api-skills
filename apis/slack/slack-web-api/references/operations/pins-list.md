# GET /pins.list

**Resource:** [pins](../resources/pins.md)
**Operation ID:** `pins_list`

Lists items pinned to a channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `pins:read` |
| `channel` | query | string | Yes | Channel to get pinned items for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: pins:read
