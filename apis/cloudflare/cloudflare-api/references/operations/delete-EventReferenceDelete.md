# DELETE /accounts/{account_id}/cloudforce-one/events/relate/{event_id}

**Resource:** [Event](../resources/Event.md)
**Removes an event reference**
**Operation ID:** `delete_EventReferenceDelete`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns success if operation succeeded. |
| 400 | Bad Request. |

## Security

- **api_token**
