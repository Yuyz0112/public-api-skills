# POST /v1/application_fees/{id}/refunds

**Resource:** [application_fees](../resources/application-fees.md)
**Create an application fee refund**
**Operation ID:** `PostApplicationFeesIdRefunds`

<p>Refunds an application fee that has previously been collected but not yet refunded.
Funds will be refunded to the Stripe account from which the fee was originally collected.</p>

<p>You can optionally refund only part of an application fee.
You can do so multiple times, until the entire fee has been refunded.</p>

<p>Once entirely refunded, an application fee can’t be refunded again.
This method will raise an error when called on an already-refunded application fee,
or when trying to refund more money than is left on an application fee.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[fee_refund](../schemas/fee/fee-refund.md)

