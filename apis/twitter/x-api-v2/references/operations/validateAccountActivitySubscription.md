# GET /2/account_activity/webhooks/{webhook_id}/subscriptions/all

**Resource:** [Account Activity](../resources/Account-Activity.md)
**Validate subscription**
**Operation ID:** `validateAccountActivitySubscription`

Checks a user’s Account Activity subscription for a given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The webhook ID to check subscription against. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubscriptionsGetResponse](../schemas/Subscriptions/SubscriptionsGetResponse.md)

## Security

- **OAuth2UserToken**: dm.read, dm.write, tweet.read, users.read
- **UserToken**
