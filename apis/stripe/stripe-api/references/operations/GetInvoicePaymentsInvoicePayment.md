# GET /v1/invoice_payments/{invoice_payment}

**Resource:** [invoice_payments](../resources/invoice-payments.md)
**Retrieve an InvoicePayment**
**Operation ID:** `GetInvoicePaymentsInvoicePayment`

<p>Retrieves the invoice payment with the given ID.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `invoice_payment` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoice_payment](../schemas/invoice/invoice-payment.md)

