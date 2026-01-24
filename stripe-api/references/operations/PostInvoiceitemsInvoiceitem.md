# POST /v1/invoiceitems/{invoiceitem}

**Resource:** [invoiceitems](../resources/invoiceitems.md)
**Update an invoice item**
**Operation ID:** `PostInvoiceitemsInvoiceitem`

<p>Updates the amount or description of an invoice item on an upcoming invoice. Updating an invoice item is only possible before the invoice it’s attached to is closed.</p>

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

[invoiceitem](../schemas/invoiceitem/invoiceitem.md)

