# issuing_card_authorization_controls

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_categories` | string[] | No | Array of strings containing [categories](https://docs.stripe.com/api#issuing_authorization_object-merchant_data-category) of authorizations to allow. All other categories will be blocked. Cannot be set with `blocked_categories`. |
| `allowed_merchant_countries` | string[] | No | Array of strings containing representing countries from which authorizations will be allowed. Authorizations from merchants in all other countries will be declined. Country codes should be ISO 3166 alpha-2 country codes (e.g. `US`). Cannot be set with `blocked_merchant_countries`. Provide an empty value to unset this control. |
| `blocked_categories` | string[] | No | Array of strings containing [categories](https://docs.stripe.com/api#issuing_authorization_object-merchant_data-category) of authorizations to decline. All other categories will be allowed. Cannot be set with `allowed_categories`. |
| `blocked_merchant_countries` | string[] | No | Array of strings containing representing countries from which authorizations will be declined. Country codes should be ISO 3166 alpha-2 country codes (e.g. `US`). Cannot be set with `allowed_merchant_countries`. Provide an empty value to unset this control. |
| `spending_limits` | issuing_card_spending_limit[] | No | Limit spending with amount-based rules that apply across any cards this card replaced (i.e., its `replacement_for` card and _that_ card's `replacement_for` card, up the chain). |
| `spending_limits_currency` | string (currency) | No | Currency of the amounts within `spending_limits`. Always the same as the currency of the card. |

