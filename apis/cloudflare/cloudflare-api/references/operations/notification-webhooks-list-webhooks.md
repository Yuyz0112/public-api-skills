# GET /accounts/{account_id}/alerting/v3/destinations/webhooks

**Resource:** [Notification webhooks](../resources/Notification-webhooks.md)
**List webhooks**
**Operation ID:** `notification-webhooks-list-webhooks`

Gets a list of all configured webhook destinations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List webhooks response |
| 4XX | List webhooks response failure |

**Success Response Schema:**

[aaa_webhooks_components-schemas-response_collection](../schemas/aaa/aaa-webhooks-components-schemas-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**
