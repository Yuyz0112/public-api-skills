# treasury.received_credit

ReceivedCredits represent funds sent to a [FinancialAccount](https://api.stripe.com#financial_accounts) (for example, via ACH or wire). These money movements are not initiated from the FinancialAccount.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount (in cents) transferred. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | Yes | An arbitrary string attached to the object. Often useful for displaying to users. |
| `failure_code` | enum: account_closed, account_frozen, international_transaction... | No | Reason for the failure. A ReceivedCredit might fail because the receiving FinancialAccount is closed or frozen. |
| `financial_account` | string | No | The FinancialAccount that received the funds. |
| `hosted_regulatory_receipt_url` | string | No | A [hosted transaction receipt](https://docs.stripe.com/treasury/moving-money/regulatory-receipts) URL that is provided when money movement is considered regulated under Stripe's money transmission licenses. |
| `id` | string | Yes | Unique identifier for the object. |
| `initiating_payment_method_details` | [treasury_shared_resource_initiating_payment_method_details_initiating_payment_method_details](treasury-shared-resource-initiating-payment-method-details-initiating-payment-method-details.md) | Yes |  |
| `linked_flows` | [treasury_received_credits_resource_linked_flows](treasury-received-credits-resource-linked-flows.md) | Yes |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `network` | enum: ach, card, stripe... | Yes | The rails used to send the funds. |
| `object` | enum: treasury.received_credit | Yes | String representing the object's type. Objects of the same type share the same value. |
| `reversal_details` | any | No | Details describing when a ReceivedCredit may be reversed. |
| `status` | enum: failed, succeeded | Yes | Status of the ReceivedCredit. ReceivedCredits are created either `succeeded` (approved) or `failed` (declined). If a ReceivedCredit is declined, the failure reason can be found in the `failure_code` field. |
| `transaction` | any | No | The Transaction associated with this object. |

