# payment_intent_next_action_konbini

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expires_at` | integer (unix-time) | Yes | The timestamp at which the pending Konbini payment expires. |
| `hosted_voucher_url` | string | No | The URL for the Konbini payment instructions page, which allows customers to view and print a Konbini voucher. |
| `stores` | [payment_intent_next_action_konbini_stores](payment-intent-next-action-konbini-stores.md) | Yes |  |

