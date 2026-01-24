# charge_transfer_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | The amount transferred to the destination account, if specified. By default, the entire charge amount is transferred to the destination account. |
| `destination` | any | Yes | ID of an existing, connected Stripe account to transfer funds to if `transfer_data` was specified in the charge request. |

