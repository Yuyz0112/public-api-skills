# GET /accounts/{account_id}/cloudforce-one/events/{event_id}/raw/{raw_id}

**Resource:** [Event](../resources/Event.md)
**Reads data for a raw event**
**Operation ID:** `get_EventRawRead`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |
| `raw_id` | path | string | Yes | Raw Event UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the raw event. |
| 400 | Bad Request. |

## Security

- **api_token**
