# POST /v1/payment_method_domains/{payment_method_domain}

**Resource:** [payment_method_domains](../resources/payment-method-domains.md)
**Update a payment method domain**
**Operation ID:** `PostPaymentMethodDomainsPaymentMethodDomain`

<p>Updates an existing payment method domain.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `payment_method_domain` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_method_domain](../schemas/payment/payment-method-domain.md)

