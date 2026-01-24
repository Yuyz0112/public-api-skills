# POST /v1/payouts/{payout}/cancel

**Resource:** [payouts](../resources/payouts.md)
**Cancel a payout**
**Operation ID:** `PostPayoutsPayoutCancel`

<p>You can cancel a previously created payout if its status is <code>pending</code>. Stripe refunds the funds to your available balance. You can’t cancel automatic Stripe payouts.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `payout` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payout](../schemas/payout/payout.md)

