# GET /v1/payment_method_domains/{payment_method_domain}

**Resource:** [payment_method_domains](../resources/payment-method-domains.md)
**Retrieve a payment method domain**
**Operation ID:** `GetPaymentMethodDomainsPaymentMethodDomain`

<p>Retrieves the details of an existing payment method domain.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

