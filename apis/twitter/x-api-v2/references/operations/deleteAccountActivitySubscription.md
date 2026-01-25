# DELETE /2/account_activity/webhooks/{webhook_id}/subscriptions/{user_id}/all

**Resource:** [Account Activity](../resources/Account-Activity.md)
**Delete subscription**
**Operation ID:** `deleteAccountActivitySubscription`

Deletes an Account Activity subscription for the given webhook and user ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The webhook ID to check subscription against. |
| `user_id` | path | UserId | Yes | User ID to unsubscribe from. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubscriptionsDeleteResponse](../schemas/Subscriptions/SubscriptionsDeleteResponse.md)

## Security

- **BearerToken**
