# PUT /accounts/{account_id}/alerting/v3/destinations/webhooks/{webhook_id}

**Resource:** [Notification webhooks](../resources/Notification-webhooks.md)
**Update a webhook**
**Operation ID:** `notification-webhooks-update-a-webhook`

Update a webhook destination.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | aaa_webhook-id | Yes |  |
| `account_id` | path | aaa_account-id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a webhook response |
| 4XX | Update a webhook response failure |

**Success Response Schema:**

[aaa_id_response](../schemas/aaa/aaa-id-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
