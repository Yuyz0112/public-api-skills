# customer_tax_location

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country` | string | Yes | The identified tax country of the customer. |
| `source` | enum: billing_address, ip_address, payment_method... | Yes | The data source used to infer the customer's location. |
| `state` | string | No | The identified tax state, county, province, or region of the customer. |

