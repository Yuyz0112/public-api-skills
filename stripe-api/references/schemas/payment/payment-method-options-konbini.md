# payment_method_options_konbini

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `confirmation_number` | string | No | An optional 10 to 11 digit numeric-only string determining the confirmation code at applicable convenience stores. |
| `expires_after_days` | integer | No | The number of calendar days (between 1 and 60) after which Konbini payment instructions will expire. For example, if a PaymentIntent is confirmed with Konbini and `expires_after_days` set to 2 on Monday JST, the instructions will expire on Wednesday 23:59:59 JST. |
| `expires_at` | integer (unix-time) | No | The timestamp at which the Konbini payment instructions will expire. Only one of `expires_after_days` or `expires_at` may be set. |
| `product_description` | string | No | A product descriptor of up to 22 characters, which will appear to customers at the convenience store. |
| `setup_future_usage` | enum: none | No | Indicates that you intend to make future payments with this PaymentIntent's payment method.

If you provide a Customer with the PaymentIntent, you can use this parameter to [attach the payment method](/payments/save-during-payment) to the Customer after the PaymentIntent is confirmed and the customer completes any required actions. If you don't provide a Customer, you can still [attach](/api/payment_methods/attach) the payment method to a Customer after the transaction completes.

If the payment method is `card_present` and isn't a digital wallet, Stripe creates and attaches a [generated_card](/api/charges/object#charge_object-payment_method_details-card_present-generated_card) payment method representing the card to the Customer instead.

When processing card payments, Stripe uses `setup_future_usage` to help you comply with regional legislation and network rules, such as [SCA](/strong-customer-authentication). |

