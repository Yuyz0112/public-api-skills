# POST /v1/payment_methods/{payment_method}

**Resource:** [payment_methods](../resources/payment-methods.md)
**Update a PaymentMethod**
**Operation ID:** `PostPaymentMethodsPaymentMethod`

<p>Updates a PaymentMethod object. A PaymentMethod must be attached to a customer to be updated.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

