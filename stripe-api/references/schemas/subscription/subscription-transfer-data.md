# subscription_transfer_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_percent` | number | No | A non-negative decimal between 0 and 100, with at most two decimal places. This represents the percentage of the subscription invoice total that will be transferred to the destination account. By default, the entire amount is transferred to the destination. |
| `destination` | any | Yes | The account where funds from the payment will be transferred to upon payment success. |

