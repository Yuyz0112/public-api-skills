# tax.settings

You can use Tax `Settings` to manage configurations used by Stripe Tax calculations.

Related guide: [Using the Settings API](https://docs.stripe.com/tax/settings-api)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaults` | [tax_product_resource_tax_settings_defaults](tax-product-resource-tax-settings-defaults.md) | Yes |  |
| `head_office` | any | No | The place where your business is located. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: tax.settings | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, pending | Yes | The status of the Tax `Settings`. |
| `status_details` | [tax_product_resource_tax_settings_status_details](tax-product-resource-tax-settings-status-details.md) | Yes |  |

