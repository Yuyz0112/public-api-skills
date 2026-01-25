# POST /v1/payouts/{payout}

**Resource:** [payouts](../resources/payouts.md)
**Update a payout**
**Operation ID:** `PostPayoutsPayout`

<p>Updates the specified payout by setting the values of the parameters you pass. We don’t change parameters that you don’t provide. This request only accepts the metadata as arguments.</p>

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

