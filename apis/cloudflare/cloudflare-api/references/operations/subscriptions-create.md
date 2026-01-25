# POST /accounts/{account_id}/event_subscriptions/subscriptions

**Resource:** [Queue](../resources/Queue.md)
**Create Event Subscription**
**Operation ID:** `subscriptions-create`

Create a new event subscription for a queue

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mq_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully created event subscription |
| 400 | Invalid request body or validation errors |
| 404 | Queue does not exist or resource not found on source |
| 405 | Multiple subscriptions on same resource not supported |

## Security

- **api_email**
- **api_key**
- **api_token**
