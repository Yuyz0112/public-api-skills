# GET /v1/invoice_rendering_templates/{template}

**Resource:** [invoice_rendering_templates](../resources/invoice-rendering-templates.md)
**Retrieve an invoice rendering template**
**Operation ID:** `GetInvoiceRenderingTemplatesTemplate`

<p>Retrieves an invoice rendering template with the given ID. It by default returns the latest version of the template. Optionally, specify a version to see previous versions.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `template` | path | string | Yes |  |
| `version` | query | integer | No |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[invoice_rendering_template](../schemas/invoice/invoice-rendering-template.md)

