# payment_method_card_present_networks

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `available` | string[] | Yes | All networks available for selection via [payment_method_options.card.network](/api/payment_intents/confirm#confirm_payment_intent-payment_method_options-card-network). |
| `preferred` | string | No | The preferred network for the card. |

