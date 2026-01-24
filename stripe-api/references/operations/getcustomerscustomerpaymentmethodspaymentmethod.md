# GET /v1/customers/{customer}/payment_methods/{payment_method}

**Resource:** [customers](../resources/customers.md)
**Retrieve a Customer's PaymentMethod**
**Operation ID:** `GetCustomersCustomerPaymentMethodsPaymentMethod`

<p>Retrieves a PaymentMethod object for a given Customer.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
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

