# GET /rtm.connect

**Resource:** [rtm](../resources/rtm.md)
**Operation ID:** `rtm_connect`

Starts a Real Time Messaging session.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `rtm:stream` |
| `batch_presence_aware` | query | boolean | No | Batch presence deliveries via subscription. Enabling changes the shape of `presence_change` events. See [batch presence](/docs/presence-and-status#batching). |
| `presence_sub` | query | boolean | No | Only deliver presence events when requested by subscription. See [presence subscriptions](/docs/presence-and-status#subscriptions). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: rtm:stream
