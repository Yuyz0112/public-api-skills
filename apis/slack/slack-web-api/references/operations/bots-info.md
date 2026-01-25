# GET /bots.info

**Resource:** [bots](../resources/bots.md)
**Operation ID:** `bots_info`

Gets information about a bot user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `users:read` |
| `bot` | query | string | No | Bot user to get info on |

## Responses

| Status | Description |
|--------|-------------|
| 200 | When successful, returns bot info by bot ID. |
| default | When no bot can be found, it returns an error. |

## Security

- **slackAuth**: users:read
