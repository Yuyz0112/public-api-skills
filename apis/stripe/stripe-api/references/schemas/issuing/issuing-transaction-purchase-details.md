# issuing_transaction_purchase_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fleet` | any | No | Fleet-specific information for transactions using Fleet cards. |
| `flight` | any | No | Information about the flight that was purchased with this transaction. |
| `fuel` | any | No | Information about fuel that was purchased with this transaction. |
| `lodging` | any | No | Information about lodging that was purchased with this transaction. |
| `receipt` | issuing_transaction_receipt_data[] | No | The line items in the purchase. |
| `reference` | string | No | A merchant-specific order number. |

