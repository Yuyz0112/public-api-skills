# issuing_transaction_fleet_tax_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `local_amount_decimal` | string (decimal) | No | Amount of state or provincial Sales Tax included in the transaction amount. Null if not reported by merchant or not subject to tax. |
| `national_amount_decimal` | string (decimal) | No | Amount of national Sales Tax or VAT included in the transaction amount. Null if not reported by merchant or not subject to tax. |

