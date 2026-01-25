# connect_embedded_payment_disputes_features

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destination_on_behalf_of_charge_management` | boolean | Yes | Whether connected accounts can manage destination charges that are created on behalf of them. This is `false` by default. |
| `dispute_management` | boolean | Yes | Whether responding to disputes is enabled, including submitting evidence and accepting disputes. This is `true` by default. |
| `refund_management` | boolean | Yes | Whether sending refunds is enabled. This is `true` by default. |

