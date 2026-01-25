# payment_pages_checkout_session_custom_fields

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dropdown` | [payment_pages_checkout_session_custom_fields_dropdown](payment-pages-checkout-session-custom-fields-dropdown.md) | No |  |
| `key` | string | Yes | String of your choice that your integration can use to reconcile this field. Must be unique to this field, alphanumeric, and up to 200 characters. |
| `label` | [payment_pages_checkout_session_custom_fields_label](payment-pages-checkout-session-custom-fields-label.md) | Yes |  |
| `numeric` | [payment_pages_checkout_session_custom_fields_numeric](payment-pages-checkout-session-custom-fields-numeric.md) | No |  |
| `optional` | boolean | Yes | Whether the customer is required to complete the field before completing the Checkout Session. Defaults to `false`. |
| `text` | [payment_pages_checkout_session_custom_fields_text](payment-pages-checkout-session-custom-fields-text.md) | No |  |
| `type` | enum: dropdown, numeric, text | Yes | The type of the field. |

