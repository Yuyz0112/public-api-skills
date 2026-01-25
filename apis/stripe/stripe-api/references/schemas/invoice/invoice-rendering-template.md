# invoice_rendering_template

Invoice Rendering Templates are used to configure how invoices are rendered on surfaces like the PDF. Invoice Rendering Templates
can be created from within the Dashboard, and they can be used over the API when creating invoices.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `nickname` | string | No | A brief description of the template, hidden from customers |
| `object` | enum: invoice_rendering_template | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, archived | Yes | The status of the template, one of `active` or `archived`. |
| `version` | integer | Yes | Version of this template; version increases by one when an update on the template changes any field that controls invoice rendering |

