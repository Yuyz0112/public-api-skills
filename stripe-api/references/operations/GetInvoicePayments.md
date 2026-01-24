# GET /v1/invoice_payments

**Resource:** [invoice_payments](../resources/invoice-payments.md)
**List all payments for an invoice**
**Operation ID:** `GetInvoicePayments`

<p>When retrieving an invoice, there is an includable payments property containing the first handful of those items. There is also a URL where you can retrieve the full (paginated) list of payments.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | any | No | Only return invoice payments that were created during the given date interval. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `invoice` | query | string | No | The identifier of the invoice whose payments to return. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `payment` | query | object | No | The payment details of the invoice payments to return. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: canceled, open, paid | No | The status of the invoice payments to return. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

