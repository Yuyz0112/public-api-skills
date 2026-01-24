# treasury_received_debits_resource_linked_flows

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `debit_reversal` | string | No | The DebitReversal created as a result of this ReceivedDebit being reversed. |
| `inbound_transfer` | string | No | Set if the ReceivedDebit is associated with an InboundTransfer's return of funds. |
| `issuing_authorization` | string | No | Set if the ReceivedDebit was created due to an [Issuing Authorization](https://api.stripe.com#issuing_authorizations) object. |
| `issuing_transaction` | string | No | Set if the ReceivedDebit is also viewable as an [Issuing Dispute](https://api.stripe.com#issuing_disputes) object. |
| `payout` | string | No | Set if the ReceivedDebit was created due to a [Payout](https://api.stripe.com#payouts) object. |
| `topup` | string | No | Set if the ReceivedDebit was created due to a [Topup](https://api.stripe.com#topups) object. |

