# POST /v1/charges/{charge}/refunds/{refund}

**Resource:** [charges](../resources/charges.md)
**Operation ID:** `PostChargesChargeRefundsRefund`

<p>Update a specified refund.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `charge` | path | string | Yes |  |
| `refund` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[refund](../schemas/refund/refund.md)

