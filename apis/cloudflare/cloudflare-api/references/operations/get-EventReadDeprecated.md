# GET /accounts/{account_id}/cloudforce-one/events/{event_id}

**Resource:** [Event](../resources/Event.md)
**Reads an event**
**Operation ID:** `get_EventReadDeprecated`
⚠️ **Deprecated**

This Method is deprecated. Please use /events/dataset/:dataset_id/events/:event_id instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns an event. |
| 404 | Bad Request. |

## Security

- **api_token**
