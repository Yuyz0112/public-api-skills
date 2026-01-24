# payment_intent_next_action_boleto

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expires_at` | integer (unix-time) | No | The timestamp after which the boleto expires. |
| `hosted_voucher_url` | string | No | The URL to the hosted boleto voucher page, which allows customers to view the boleto voucher. |
| `number` | string | No | The boleto number. |
| `pdf` | string | No | The URL to the downloadable boleto voucher PDF. |

