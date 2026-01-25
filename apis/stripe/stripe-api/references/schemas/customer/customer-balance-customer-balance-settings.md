# customer_balance_customer_balance_settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `reconciliation_mode` | enum: automatic, manual | Yes | The configuration for how funds that land in the customer cash balance are reconciled. |
| `using_merchant_default` | boolean | Yes | A flag to indicate if reconciliation mode returned is the user's default or is specific to this customer cash balance |

