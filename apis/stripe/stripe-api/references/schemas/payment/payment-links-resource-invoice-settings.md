# payment_links_resource_invoice_settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_tax_ids` | any[] | No | The account tax IDs associated with the invoice. |
| `custom_fields` | invoice_setting_custom_field[] | No | A list of up to 4 custom fields to be displayed on the invoice. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `footer` | string | No | Footer to be displayed on the invoice. |
| `issuer` | any | No | The connected account that issues the invoice. The invoice is presented with the branding and support information of the specified account. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `rendering_options` | any | No | Options for invoice PDF rendering. |

