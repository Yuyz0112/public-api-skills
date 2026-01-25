# GET /radar/bots/{bot_slug}

**Resource:** [Radar Bots](../resources/Radar-Bots.md)
**Get bot details**
**Operation ID:** `radar-get-bot-details`

Retrieves the requested bot information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bot_slug` | path | string | Yes | Bot slug. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 404 | Not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
