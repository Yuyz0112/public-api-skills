# GET /v1/invoices/{invoice}

**Resource:** [invoices](../resources/invoices.md)
**Retrieve an invoice**
**Operation ID:** `GetInvoicesInvoice`

<p>Retrieves the invoice with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `invoice` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoice](../schemas/invoice/invoice.md)

