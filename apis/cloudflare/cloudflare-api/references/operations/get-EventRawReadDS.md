# GET /accounts/{account_id}/cloudforce-one/events/raw/{dataset_id}/{event_id}

**Resource:** [Event](../resources/Event.md)
**Reads data for a raw event**
**Operation ID:** `get_EventRawReadDS`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event ID. |
| `dataset_id` | path | string | Yes | Dataset ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the raw event. |
| 400 | Bad Request. |

## Security

- **api_token**
