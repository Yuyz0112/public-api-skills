# deleted_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currency` | string | No | Three-letter [ISO code for the currency](https://stripe.com/docs/payouts) paid out to the bank account. |
| `deleted` | enum: true | Yes | Always true for a deleted object |
| `id` | string | Yes | Unique identifier for the object. |
| `object` | enum: card | Yes | String representing the object's type. Objects of the same type share the same value. |

