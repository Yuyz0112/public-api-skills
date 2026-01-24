# POST /v1/subscriptions

**Resource:** [subscriptions](../resources/subscriptions.md)
**Create a subscription**
**Operation ID:** `PostSubscriptions`

<p>Creates a new subscription on an existing customer. Each customer can have up to 500 active or scheduled subscriptions.</p>

<p>When you create a subscription with <code>collection_method=charge_automatically</code>, the first invoice is finalized as part of the request.
The <code>payment_behavior</code> parameter determines the exact behavior of the initial payment.</p>

<p>To start subscriptions where the first invoice always begins in a <code>draft</code> status, use <a href="/docs/billing/subscriptions/subscription-schedules#managing">subscription schedules</a> instead.
Schedules provide the flexibility to model more complex billing configurations that change over time.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[subscription](../schemas/subscription/subscription.md)

