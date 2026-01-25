# inbound_transfers

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_details` | [treasury_shared_resource_billing_details](treasury-shared-resource-billing-details.md) | Yes |  |
| `type` | enum: us_bank_account | Yes | The type of the payment method used in the InboundTransfer. |
| `us_bank_account` | [inbound_transfers_payment_method_details_us_bank_account](inbound-transfers-payment-method-details-us-bank-account.md) | No |  |

