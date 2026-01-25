# connect_embedded_issuing_cards_list_features

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_management` | boolean | Yes | Whether to allow card management features. |
| `card_spend_dispute_management` | boolean | Yes | Whether to allow card spend dispute management features. |
| `cardholder_management` | boolean | Yes | Whether to allow cardholder management features. |
| `disable_stripe_user_authentication` | boolean | Yes | Whether Stripe user authentication is disabled. This value can only be `true` for accounts where `controller.requirement_collection` is `application` for the account. The default value is the opposite of the `external_account_collection` value. For example, if you don't set `external_account_collection`, it defaults to `true` and `disable_stripe_user_authentication` defaults to `false`. |
| `spend_control_management` | boolean | Yes | Whether to allow spend control management features. |

