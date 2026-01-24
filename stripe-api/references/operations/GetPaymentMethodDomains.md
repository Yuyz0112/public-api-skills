# GET /v1/payment_method_domains

**Resource:** [payment_method_domains](../resources/payment-method-domains.md)
**List payment method domains**
**Operation ID:** `GetPaymentMethodDomains`

<p>Lists the details of existing payment method domains.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `domain_name` | query | string | No | The domain name that this payment method domain object represents. |
| `enabled` | query | boolean | No | Whether this payment method domain is enabled. If the domain is not enabled, payment methods will not appear in Elements or Embedded Checkout |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

