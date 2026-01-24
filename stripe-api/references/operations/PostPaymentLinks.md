# POST /v1/payment_links

**Resource:** [payment_links](../resources/payment-links.md)
**Create a payment link**
**Operation ID:** `PostPaymentLinks`

<p>Creates a payment link.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_link](../schemas/payment/payment-link.md)

