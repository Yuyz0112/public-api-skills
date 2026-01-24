# GET /v1/payment_methods/{payment_method}

**Resource:** [payment_methods](../resources/payment-methods.md)
**Retrieve a PaymentMethod**
**Operation ID:** `GetPaymentMethodsPaymentMethod`

<p>Retrieves a PaymentMethod object attached to the StripeAccount. To retrieve a payment method attached to a Customer, you should use <a href="/docs/api/payment_methods/customer">Retrieve a Customer’s PaymentMethods</a></p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `payment_method` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[payment_method](../schemas/payment/payment-method.md)

