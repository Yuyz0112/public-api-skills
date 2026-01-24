# POST /v1/refunds/{refund}/cancel

**Resource:** [refunds](../resources/refunds.md)
**Cancel a refund**
**Operation ID:** `PostRefundsRefundCancel`

<p>Cancels a refund with a status of <code>requires_action</code>.</p>

<p>You can’t cancel refunds in other states. Only refunds for payment methods that require customer action can enter the <code>requires_action</code> state.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

