# connect_embedded_payments_features

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `capture_payments` | boolean | Yes | Whether to allow capturing and cancelling payment intents. This is `true` by default. |
| `destination_on_behalf_of_charge_management` | boolean | Yes | Whether connected accounts can manage destination charges that are created on behalf of them. This is `false` by default. |
| `dispute_management` | boolean | Yes | Whether responding to disputes is enabled, including submitting evidence and accepting disputes. This is `true` by default. |
| `refund_management` | boolean | Yes | Whether sending refunds is enabled. This is `true` by default. |

