# POST /v1/payment_methods/{payment_method}/detach

**Resource:** [payment_methods](../resources/payment-methods.md)
**Detach a PaymentMethod from a Customer**
**Operation ID:** `PostPaymentMethodsPaymentMethodDetach`

<p>Detaches a PaymentMethod object from a Customer. After a PaymentMethod is detached, it can no longer be used for a payment or re-attached to a Customer.</p>

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

