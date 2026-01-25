# POST /v1/invoiceitems

**Resource:** [invoiceitems](../resources/invoiceitems.md)
**Create an invoice item**
**Operation ID:** `PostInvoiceitems`

<p>Creates an item to be added to a draft invoice (up to 250 items per invoice). If no invoice is specified, the item will be on the next invoice created for the customer specified.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoiceitem](../schemas/invoiceitem/invoiceitem.md)

