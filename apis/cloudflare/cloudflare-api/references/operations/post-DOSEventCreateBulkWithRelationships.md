# POST /accounts/{account_id}/cloudforce-one/events/create/bulk/relationships

**Resource:** [Event](../resources/Event.md)
**Creates bulk DOS event with relationships and indicators**
**Operation ID:** `post_DOSEventCreateBulkWithRelationships`
⚠️ **Deprecated**

This method is deprecated. Please use `event_create_bulk` instead

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the number of created bulk events with relationships. |
| 400 | Bad Request. |

## Security

- **api_token**
