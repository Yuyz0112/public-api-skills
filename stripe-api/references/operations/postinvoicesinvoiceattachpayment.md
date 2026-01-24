# POST /v1/invoices/{invoice}/attach_payment

**Resource:** [invoices](../resources/invoices.md)
**Attach a payment to an Invoice**
**Operation ID:** `PostInvoicesInvoiceAttachPayment`

<p>Attaches a PaymentIntent or an Out of Band Payment to the invoice, adding it to the list of <code>payments</code>.</p>

<p>For the PaymentIntent, when the PaymentIntent’s status changes to <code>succeeded</code>, the payment is credited
to the invoice, increasing its <code>amount_paid</code>. When the invoice is fully paid, the
invoice’s status becomes <code>paid</code>.</p>

<p>If the PaymentIntent’s status is already <code>succeeded</code> when it’s attached, it’s
credited to the invoice immediately.</p>

<p>See: <a href="/docs/invoicing/partial-payments">Partial payments</a> to learn more.</p>

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

