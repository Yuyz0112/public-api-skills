# POST /v1/payment_links/{payment_link}

**Resource:** [payment_links](../resources/payment-links.md)
**Update a payment link**
**Operation ID:** `PostPaymentLinksPaymentLink`

<p>Updates a payment link.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

