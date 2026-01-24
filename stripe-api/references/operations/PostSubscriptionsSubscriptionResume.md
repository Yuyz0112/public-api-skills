# POST /v1/subscriptions/{subscription}/resume

**Resource:** [subscriptions](../resources/subscriptions.md)
**Resume a subscription**
**Operation ID:** `PostSubscriptionsSubscriptionResume`

<p>Initiates resumption of a paused subscription, optionally resetting the billing cycle anchor and creating prorations. If a resumption invoice is generated, it must be paid or marked uncollectible before the subscription will be unpaused. If payment succeeds the subscription will become <code>active</code>, and if payment fails the subscription will be <code>past_due</code>. The resumption invoice will void automatically if not paid by the expiration date.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `subscription` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription](../schemas/subscription/subscription.md)

