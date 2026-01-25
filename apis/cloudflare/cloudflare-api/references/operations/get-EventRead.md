# GET /accounts/{account_id}/cloudforce-one/events/dataset/{dataset_id}/events/{event_id}

**Resource:** [Event](../resources/Event.md)
**Reads an event**
**Operation ID:** `get_EventRead`

Retrieves a specific event by its UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `dataset_id` | path | string | Yes | Dataset ID. |
| `event_id` | path | string | Yes | Event UUID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the event. |
| 404 | Bad Request. |

## Security

- **api_token**
