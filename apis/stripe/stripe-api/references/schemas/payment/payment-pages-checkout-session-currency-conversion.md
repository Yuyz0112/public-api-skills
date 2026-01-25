# payment_pages_checkout_session_currency_conversion

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_subtotal` | integer | Yes | Total of all items in source currency before discounts or taxes are applied. |
| `amount_total` | integer | Yes | Total of all items in source currency after discounts and taxes are applied. |
| `fx_rate` | string (decimal) | Yes | Exchange rate used to convert source currency amounts to customer currency amounts |
| `source_currency` | string | Yes | Creation currency of the CheckoutSession before localization |

