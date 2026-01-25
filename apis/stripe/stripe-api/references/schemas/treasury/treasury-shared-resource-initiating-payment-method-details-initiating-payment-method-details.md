# treasury_shared_resource_initiating_payment_method_details_initiating_payment_method_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `balance` | enum: payments | No | Set when `type` is `balance`. |
| `billing_details` | [treasury_shared_resource_billing_details](treasury-shared-resource-billing-details.md) | Yes |  |
| `financial_account` | [received_payment_method_details_financial_account](received-payment-method-details-financial-account.md) | No |  |
| `issuing_card` | string | No | Set when `type` is `issuing_card`. This is an [Issuing Card](https://api.stripe.com#issuing_cards) ID. |
| `type` | enum: balance, financial_account, issuing_card... | Yes | Polymorphic type matching the originating money movement's source. This can be an external account, a Stripe balance, or a FinancialAccount. |
| `us_bank_account` | [treasury_shared_resource_initiating_payment_method_details_us_bank_account](treasury-shared-resource-initiating-payment-method-details-us-bank-account.md) | No |  |

