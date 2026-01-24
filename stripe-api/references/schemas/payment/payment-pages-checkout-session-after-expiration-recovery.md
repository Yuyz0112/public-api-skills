# payment_pages_checkout_session_after_expiration_recovery

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_promotion_codes` | boolean | Yes | Enables user redeemable promotion codes on the recovered Checkout Sessions. Defaults to `false` |
| `enabled` | boolean | Yes | If `true`, a recovery url will be generated to recover this Checkout Session if it
expires before a transaction is completed. It will be attached to the
Checkout Session object upon expiration. |
| `expires_at` | integer (unix-time) | No | The timestamp at which the recovery URL will expire. |
| `url` | string | No | URL that creates a new Checkout Session when clicked that is a copy of this expired Checkout Session |

