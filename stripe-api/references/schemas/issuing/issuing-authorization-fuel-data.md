# issuing_authorization_fuel_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `industry_product_code` | string | No | [Conexxus Payment System Product Code](https://www.conexxus.org/conexxus-payment-system-product-codes) identifying the primary fuel product purchased. |
| `quantity_decimal` | string (decimal) | No | The quantity of `unit`s of fuel that was dispensed, represented as a decimal string with at most 12 decimal places. |
| `type` | enum: diesel, other, unleaded_plus... | No | The type of fuel that was purchased. |
| `unit` | enum: charging_minute, imperial_gallon, kilogram... | No | The units for `quantity_decimal`. |
| `unit_cost_decimal` | string (decimal) | No | The cost in cents per each unit of fuel, represented as a decimal string with at most 12 decimal places. |

