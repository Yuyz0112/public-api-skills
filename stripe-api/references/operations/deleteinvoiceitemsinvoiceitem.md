# DELETE /v1/invoiceitems/{invoiceitem}

**Resource:** [invoiceitems](../resources/invoiceitems.md)
**Delete an invoice item**
**Operation ID:** `DeleteInvoiceitemsInvoiceitem`

<p>Deletes an invoice item, removing it from an invoice. Deleting invoice items is only possible when they’re not attached to invoices, or if it’s attached to a draft invoice.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `invoiceitem` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_invoiceitem](../schemas/deleted/deleted-invoiceitem.md)

