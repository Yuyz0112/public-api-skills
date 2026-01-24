# POST /v1/invoices

**Resource:** [invoices](../resources/invoices.md)
**Create an invoice**
**Operation ID:** `PostInvoices`

<p>This endpoint creates a draft invoice for a given customer. The invoice remains a draft until you <a href="#finalize_invoice">finalize</a> the invoice, which allows you to <a href="/api/invoices/pay">pay</a> or <a href="/api/invoices/send">send</a> the invoice to your customers.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoice](../schemas/invoice/invoice.md)

