# GET /v1/invoiceitems

**Resource:** [invoiceitems](../resources/invoiceitems.md)
**List all invoice items**
**Operation ID:** `GetInvoiceitems`

<p>Returns a list of your invoice items. Invoice items are returned sorted by creation date, with the most recently created invoice items appearing first.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created` | query | any | No | Only return invoice items that were created during the given date interval. |
| `customer` | query | string | No | The identifier of the customer whose invoice items to return. If none is provided, returns all invoice items. |
| `customer_account` | query | string | No | The identifier of the account representing the customer whose invoice items to return. If none is provided, returns all invoice items. |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `invoice` | query | string | No | Only return invoice items belonging to this invoice. If none is provided, all invoice items will be returned. If specifying an invoice, no customer identifier is needed. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `pending` | query | boolean | No | Set to `true` to only show pending invoice items, which are not yet attached to any invoices. Set to `false` to only show invoice items already attached to invoices. If unspecified, no filter is applied. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

