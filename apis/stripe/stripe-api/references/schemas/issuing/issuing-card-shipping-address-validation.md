# issuing_card_shipping_address_validation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mode` | enum: disabled, normalization_only, validation_and_normalization | Yes | The address validation capabilities to use. |
| `normalized_address` | any | No | The normalized shipping address. |
| `result` | enum: indeterminate, likely_deliverable, likely_undeliverable | No | The validation result for the shipping address. |

