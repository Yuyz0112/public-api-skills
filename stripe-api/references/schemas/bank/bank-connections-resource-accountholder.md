# bank_connections_resource_accountholder

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | any | No | The ID of the Stripe account that this account belongs to. Only available when `account_holder.type` is `account`. |
| `customer` | any | No | The ID for an Account representing a customer that this account belongs to. Only available when `account_holder.type` is `customer`. |
| `customer_account` | string | No |  |
| `type` | enum: account, customer | Yes | Type of account holder that this account belongs to. |

