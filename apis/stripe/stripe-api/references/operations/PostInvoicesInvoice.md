# POST /v1/invoices/{invoice}

**Resource:** [invoices](../resources/invoices.md)
**Update an invoice**
**Operation ID:** `PostInvoicesInvoice`

<p>Draft invoices are fully editable. Once an invoice is <a href="/docs/billing/invoices/workflow#finalized">finalized</a>,
monetary values, as well as <code>collection_method</code>, become uneditable.</p>

<p>If you would like to stop the Stripe Billing engine from automatically finalizing, reattempting payments on,
sending reminders for, or <a href="/docs/billing/invoices/reconciliation">automatically reconciling</a> invoices, pass
<code>auto_advance=false</code>.</p>

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

