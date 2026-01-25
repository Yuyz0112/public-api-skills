# payment_method_domain

A payment method domain represents a web domain that you have registered with Stripe.
Stripe Elements use registered payment method domains to control where certain payment methods are shown.

Related guide: [Payment method domains](https://docs.stripe.com/payments/payment-methods/pmd-registration).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amazon_pay` | [payment_method_domain_resource_payment_method_status](payment-method-domain-resource-payment-method-status.md) | Yes |  |
| `apple_pay` | [payment_method_domain_resource_payment_method_status](payment-method-domain-resource-payment-method-status.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `domain_name` | string | Yes | The domain name that this payment method domain object represents. |
| `enabled` | boolean | Yes | Whether this payment method domain is enabled. If the domain is not enabled, payment methods that require a payment method domain will not appear in Elements. |
| `google_pay` | [payment_method_domain_resource_payment_method_status](payment-method-domain-resource-payment-method-status.md) | Yes |  |
| `id` | string | Yes | Unique identifier for the object. |
| `klarna` | [payment_method_domain_resource_payment_method_status](payment-method-domain-resource-payment-method-status.md) | Yes |  |
| `link` | [payment_method_domain_resource_payment_method_status](payment-method-domain-resource-payment-method-status.md) | Yes |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: payment_method_domain | Yes | String representing the object's type. Objects of the same type share the same value. |
| `paypal` | [payment_method_domain_resource_payment_method_status](payment-method-domain-resource-payment-method-status.md) | Yes |  |

