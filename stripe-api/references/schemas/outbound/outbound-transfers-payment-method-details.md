# outbound_transfers_payment_method_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_details` | [treasury_shared_resource_billing_details](treasury-shared-resource-billing-details.md) | Yes |  |
| `financial_account` | [outbound_transfers_payment_method_details_financial_account](outbound-transfers-payment-method-details-financial-account.md) | No |  |
| `type` | enum: financial_account, us_bank_account | Yes | The type of the payment method used in the OutboundTransfer. |
| `us_bank_account` | [outbound_transfers_payment_method_details_us_bank_account](outbound-transfers-payment-method-details-us-bank-account.md) | No |  |

