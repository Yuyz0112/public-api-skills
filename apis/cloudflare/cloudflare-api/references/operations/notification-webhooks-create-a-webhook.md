# POST /accounts/{account_id}/alerting/v3/destinations/webhooks

**Resource:** [Notification webhooks](../resources/Notification-webhooks.md)
**Create a webhook**
**Operation ID:** `notification-webhooks-create-a-webhook`

Creates a new webhook destination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | aaa_account-id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create a webhook response |
| 4XX | Create a webhook response failure |

**Success Response Schema:**

[aaa_id_response](../schemas/aaa/aaa-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
