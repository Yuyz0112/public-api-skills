# tax_i_ds_owner

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | any | No | The account being referenced when `type` is `account`. |
| `application` | any | No | The Connect Application being referenced when `type` is `application`. |
| `customer` | any | No | The customer being referenced when `type` is `customer`. |
| `customer_account` | string | No | The Account representing the customer being referenced when `type` is `customer`. |
| `type` | enum: account, application, customer... | Yes | Type of owner referenced. |

