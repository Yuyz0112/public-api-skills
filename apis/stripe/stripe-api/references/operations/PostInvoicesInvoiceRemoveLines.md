# POST /v1/invoices/{invoice}/remove_lines

**Resource:** [invoices](../resources/invoices.md)
**Bulk remove invoice line items**
**Operation ID:** `PostInvoicesInvoiceRemoveLines`

<p>Removes multiple line items from an invoice. This is only possible when an invoice is still a draft.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `invoice` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoice](../schemas/invoice/invoice.md)

