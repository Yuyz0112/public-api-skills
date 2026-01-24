# POST /v1/payment_method_domains/{payment_method_domain}/validate

**Resource:** [payment_method_domains](../resources/payment-method-domains.md)
**Validate an existing payment method domain**
**Operation ID:** `PostPaymentMethodDomainsPaymentMethodDomainValidate`

<p>Some payment methods might require additional steps to register a domain. If the requirements weren’t satisfied when the domain was created, the payment method will be inactive on the domain.
The payment method doesn’t appear in Elements or Embedded Checkout for this domain until it is active.</p>

<p>To activate a payment method on an existing payment method domain, complete the required registration steps specific to the payment method, and then validate the payment method domain with this endpoint.</p>

<p>Related guides: <a href="/docs/payments/payment-methods/pmd-registration">Payment method domains</a>.</p>

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

