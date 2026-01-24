# networks

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `available` | string[] | Yes | All networks available for selection via [payment_method_options.card.network](/api/payment_intents/confirm#confirm_payment_intent-payment_method_options-card-network). |
| `preferred` | string | No | The preferred network for co-branded cards. Can be `cartes_bancaires`, `mastercard`, `visa` or `invalid_preference` if requested network is not valid for the card. |

