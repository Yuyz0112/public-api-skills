# GET /v1/treasury/outbound_payments/{id}

**Resource:** [treasury](../resources/treasury.md)
**Retrieve an OutboundPayment**
**Operation ID:** `GetTreasuryOutboundPaymentsId`

<p>Retrieves the details of an existing OutboundPayment by passing the unique OutboundPayment ID from either the OutboundPayment creation request or OutboundPayment list.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[treasury.outbound_payment](../schemas/treasury-outbound/treasury-outbound-payment.md)

