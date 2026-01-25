# POST /pins.remove

**Resource:** [pins](../resources/pins.md)
**Operation ID:** `pins_remove`

Un-pins an item from a channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `pins:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: pins:write
