# GET /invites/{code}

**Resource:** [invites](../resources/invites.md)
**Operation ID:** `invite_resolve`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_counts` | query | boolean | No |  |
| `guild_scheduled_event_id` | query | SnowflakeType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for invite_resolve |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
