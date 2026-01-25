# GET /v1/payment_links/{payment_link}

**Resource:** [payment_links](../resources/payment-links.md)
**Retrieve payment link**
**Operation ID:** `GetPaymentLinksPaymentLink`

<p>Retrieve a payment link.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `payment_link` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_link](../schemas/payment/payment-link.md)

