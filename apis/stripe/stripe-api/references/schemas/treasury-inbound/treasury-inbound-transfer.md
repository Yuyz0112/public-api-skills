# treasury.inbound_transfer

Use [InboundTransfers](https://docs.stripe.com/docs/treasury/moving-money/financial-accounts/into/inbound-transfers) to add funds to your [FinancialAccount](https://api.stripe.com#financial_accounts) via a PaymentMethod that is owned by you. The funds will be transferred via an ACH debit.

Related guide: [Moving money with Treasury using InboundTransfer objects](https://docs.stripe.com/docs/treasury/moving-money/financial-accounts/into/inbound-transfers)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount (in cents) transferred. |
| `cancelable` | boolean | Yes | Returns `true` if the InboundTransfer is able to be canceled. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `failure_details` | any | No | Details about this InboundTransfer's failure. Only set when status is `failed`. |
| `financial_account` | string | Yes | The FinancialAccount that received the funds. |
| `hosted_regulatory_receipt_url` | string | No | A [hosted transaction receipt](https://docs.stripe.com/treasury/moving-money/regulatory-receipts) URL that is provided when money movement is considered regulated under Stripe's money transmission licenses. |
| `id` | string | Yes | Unique identifier for the object. |
| `linked_flows` | [treasury_inbound_transfers_resource_inbound_transfer_resource_linked_flows](treasury-inbound-transfers-resource-inbound-transfer-resource-linked-flows.md) | Yes |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: treasury.inbound_transfer | Yes | String representing the object's type. Objects of the same type share the same value. |
| `origin_payment_method` | string | No | The origin payment method to be debited for an InboundTransfer. |
| `origin_payment_method_details` | any | No | Details about the PaymentMethod for an InboundTransfer. |
| `returned` | boolean | No | Returns `true` if the funds for an InboundTransfer were returned after the InboundTransfer went to the `succeeded` state. |
| `statement_descriptor` | string | Yes | Statement descriptor shown when funds are debited from the source. Not all payment networks support `statement_descriptor`. |
| `status` | enum: canceled, failed, processing... | Yes | Status of the InboundTransfer: `processing`, `succeeded`, `failed`, and `canceled`. An InboundTransfer is `processing` if it is created and pending. The status changes to `succeeded` once the funds have been "confirmed" and a `transaction` is created and posted. The status changes to `failed` if the transfer fails. |
| `status_transitions` | [treasury_inbound_transfers_resource_inbound_transfer_resource_status_transitions](treasury-inbound-transfers-resource-inbound-transfer-resource-status-transitions.md) | Yes |  |
| `transaction` | any | No | The Transaction associated with this object. |

