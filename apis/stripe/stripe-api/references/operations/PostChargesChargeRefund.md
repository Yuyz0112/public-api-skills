# POST /v1/charges/{charge}/refund

**Resource:** [charges](../resources/charges.md)
**Create a refund**
**Operation ID:** `PostChargesChargeRefund`

<p>When you create a new refund, you must specify either a Charge or a PaymentIntent object.</p>

<p>This action refunds a previously created charge that’s not refunded yet.
Funds are refunded to the credit or debit card that’s originally charged.</p>

<p>You can optionally refund only part of a charge.
You can repeat this until the entire charge is refunded.</p>

<p>After you entirely refund a charge, you can’t refund it again.
This method raises an error when it’s called on an already-refunded charge,
or when you attempt to refund more money than is left on a charge.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `charge` | path | string | Yes | The identifier of the charge to refund. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[charge](../schemas/charge/charge.md)

