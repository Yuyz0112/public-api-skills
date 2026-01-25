# issuing_cardholder_spending_limit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Maximum amount allowed to spend per interval. This amount is in the card's currency and in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `categories` | string[] | No | Array of strings containing [categories](https://docs.stripe.com/api#issuing_authorization_object-merchant_data-category) this limit applies to. Omitting this field will apply the limit to all categories. |
| `interval` | enum: all_time, daily, monthly... | Yes | Interval (or event) to which the amount applies. |

