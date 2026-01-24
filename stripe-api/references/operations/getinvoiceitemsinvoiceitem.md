# GET /v1/invoiceitems/{invoiceitem}

**Resource:** [invoiceitems](../resources/invoiceitems.md)
**Retrieve an invoice item**
**Operation ID:** `GetInvoiceitemsInvoiceitem`

<p>Retrieves the invoice item with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
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

