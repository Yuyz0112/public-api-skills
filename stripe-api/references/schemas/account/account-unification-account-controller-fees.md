# account_unification_account_controller_fees

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `payer` | enum: account, application, application_custom... | Yes | A value indicating the responsible payer of a bundle of Stripe fees for pricing-control eligible products on this account. Learn more about [fee behavior on connected accounts](https://docs.stripe.com/connect/direct-charges-fee-payer-behavior). |

