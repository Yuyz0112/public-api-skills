# payment_pages_checkout_session_branding_settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `background_color` | string | Yes | A hex color value starting with `#` representing the background color for the Checkout Session. |
| `border_style` | enum: pill, rectangular, rounded | Yes | The border style for the Checkout Session. Must be one of `rounded`, `rectangular`, or `pill`. |
| `button_color` | string | Yes | A hex color value starting with `#` representing the button color for the Checkout Session. |
| `display_name` | string | Yes | The display name shown on the Checkout Session. |
| `font_family` | string | Yes | The font family for the Checkout Session. Must be one of the [supported font families](https://docs.stripe.com/payments/checkout/customization/appearance?payment-ui=stripe-hosted#font-compatibility). |
| `icon` | any | No | The icon for the Checkout Session. You cannot set both `logo` and `icon`. |
| `logo` | any | No | The logo for the Checkout Session. You cannot set both `logo` and `icon`. |

