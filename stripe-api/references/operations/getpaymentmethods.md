# GET /v1/payment_methods

**Resource:** [payment_methods](../resources/payment-methods.md)
**List PaymentMethods**
**Operation ID:** `GetPaymentMethods`

<p>Returns a list of all PaymentMethods.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `allow_redisplay` | query | enum: always, limited, unspecified | No | This field indicates whether this payment method can be shown again to its customer in a checkout flow. Stripe products such as Checkout and Elements use this field to determine whether a payment method can be shown as a saved payment method in a checkout flow. |
| `customer` | query | string | No | The ID of the customer whose PaymentMethods will be retrieved. |
| `customer_account` | query | string | No | The ID of the Account whose PaymentMethods will be retrieved. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `type` | query | enum: acss_debit, affirm, afterpay_clearpay... | No | Filters the list by the object `type` field. Unfiltered, the list returns all payment method types except `custom`. If your integration expects only one type of payment method in the response, specify that type value in the request to reduce your payload. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

