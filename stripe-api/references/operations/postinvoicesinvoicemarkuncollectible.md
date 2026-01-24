# POST /v1/invoices/{invoice}/mark_uncollectible

**Resource:** [invoices](../resources/invoices.md)
**Mark an invoice as uncollectible**
**Operation ID:** `PostInvoicesInvoiceMarkUncollectible`

<p>Marking an invoice as uncollectible is useful for keeping track of bad debts that can be written off for accounting purposes.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

