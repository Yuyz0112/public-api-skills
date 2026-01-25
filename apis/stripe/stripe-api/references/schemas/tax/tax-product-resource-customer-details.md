# tax_product_resource_customer_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | any | No | The customer's postal address (for example, home or business location). |
| `address_source` | enum: billing, shipping | No | The type of customer address provided. |
| `ip_address` | string | No | The customer's IP address (IPv4 or IPv6). |
| `tax_ids` | tax_product_resource_customer_details_resource_tax_id[] | Yes | The customer's tax IDs (for example, EU VAT numbers). |
| `taxability_override` | enum: customer_exempt, none, reverse_charge | Yes | The taxability override used for taxation. |

