# POST /2/account_activity/webhooks/{webhook_id}/subscriptions/all

**Resource:** [Account Activity](../resources/Account-Activity.md)
**Create subscription**
**Operation ID:** `createAccountActivitySubscription`

Creates an Account Activity subscription for the user and the given webhook.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `webhook_id` | path | WebhookConfigId | Yes | The webhook ID to check subscription against. |

## Request Body

**Content Types:** `application/json`

**Schema:** [SubscriptionsCreateRequest](../schemas/Subscriptions/SubscriptionsCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubscriptionsCreateResponse](../schemas/Subscriptions/SubscriptionsCreateResponse.md)

## Security

- **OAuth2UserToken**: dm.read, dm.write, tweet.read, users.read
- **UserToken**
