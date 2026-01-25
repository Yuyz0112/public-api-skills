# GET /2/account_activity/webhooks/{webhook_id}/subscriptions/all/list

**Resource:** [Account Activity](../resources/Account-Activity.md)
**Get subscriptions**
**Operation ID:** `getAccountActivitySubscriptions`

Retrieves a list of all active subscriptions for a given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The webhook ID to pull subscriptions for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubscriptionsListGetResponse](../schemas/Subscriptions/SubscriptionsListGetResponse.md)

## Security

- **BearerToken**
