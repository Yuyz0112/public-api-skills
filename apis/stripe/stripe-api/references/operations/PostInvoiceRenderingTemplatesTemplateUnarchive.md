# POST /v1/invoice_rendering_templates/{template}/unarchive

**Resource:** [invoice_rendering_templates](../resources/invoice-rendering-templates.md)
**Unarchive an invoice rendering template**
**Operation ID:** `PostInvoiceRenderingTemplatesTemplateUnarchive`

<p>Unarchive an invoice rendering template so it can be used on new Stripe objects again.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `template` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoice_rendering_template](../schemas/invoice/invoice-rendering-template.md)

