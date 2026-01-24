# GET /v1/invoices

**Resource:** [invoices](../resources/invoices.md)
**List all invoices**
**Operation ID:** `GetInvoices`

<p>You can list all invoices, or list the invoices for a specific customer. The invoices are returned sorted by creation date, with the most recently created invoices appearing first.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `collection_method` | query | enum: charge_automatically, send_invoice | No | The collection method of the invoice to retrieve. Either `charge_automatically` or `send_invoice`. |
| `created` | query | any | No | Only return invoices that were created during the given date interval. |
| `customer` | query | string | No | Only return invoices for the customer specified by this customer ID. |
| `customer_account` | query | string | No | Only return invoices for the account representing the customer specified by this account ID. |
| `due_date` | query | any | No |  |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: draft, open, paid... | No | The status of the invoice, one of `draft`, `open`, `paid`, `uncollectible`, or `void`. [Learn more](https://docs.stripe.com/billing/invoices/workflow#workflow-overview) |
| `subscription` | query | string | No | Only return invoices for the subscription specified by this subscription ID. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

