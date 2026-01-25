# tax_product_registrations_resource_country_options_united_states

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `local_amusement_tax` | [tax_product_registrations_resource_country_options_us_local_amusement_tax](tax-product-registrations-resource-country-options-us-local-amusement-tax.md) | No |  |
| `local_lease_tax` | [tax_product_registrations_resource_country_options_us_local_lease_tax](tax-product-registrations-resource-country-options-us-local-lease-tax.md) | No |  |
| `state` | string | Yes | Two-letter US state code ([ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-2)). |
| `state_sales_tax` | [tax_product_registrations_resource_country_options_us_state_sales_tax](tax-product-registrations-resource-country-options-us-state-sales-tax.md) | No |  |
| `type` | enum: local_amusement_tax, local_lease_tax, state_communications_tax... | Yes | Type of registration in the US. |

