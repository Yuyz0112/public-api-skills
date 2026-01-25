# issuing_transaction_fuel_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `industry_product_code` | string | No | [Conexxus Payment System Product Code](https://www.conexxus.org/conexxus-payment-system-product-codes) identifying the primary fuel product purchased. |
| `quantity_decimal` | string (decimal) | No | The quantity of `unit`s of fuel that was dispensed, represented as a decimal string with at most 12 decimal places. |
| `type` | string | Yes | The type of fuel that was purchased. One of `diesel`, `unleaded_plus`, `unleaded_regular`, `unleaded_super`, or `other`. |
| `unit` | string | Yes | The units for `quantity_decimal`. One of `charging_minute`, `imperial_gallon`, `kilogram`, `kilowatt_hour`, `liter`, `pound`, `us_gallon`, or `other`. |
| `unit_cost_decimal` | string (decimal) | Yes | The cost in cents per each unit of fuel, represented as a decimal string with at most 12 decimal places. |

