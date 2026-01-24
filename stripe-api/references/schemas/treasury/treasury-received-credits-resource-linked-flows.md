# treasury_received_credits_resource_linked_flows

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `credit_reversal` | string | No | The CreditReversal created as a result of this ReceivedCredit being reversed. |
| `issuing_authorization` | string | No | Set if the ReceivedCredit was created due to an [Issuing Authorization](https://api.stripe.com#issuing_authorizations) object. |
| `issuing_transaction` | string | No | Set if the ReceivedCredit is also viewable as an [Issuing transaction](https://api.stripe.com#issuing_transactions) object. |
| `source_flow` | string | No | ID of the source flow. Set if `network` is `stripe` and the source flow is visible to the user. Examples of source flows include OutboundPayments, payouts, or CreditReversals. |
| `source_flow_details` | any | No | The expandable object of the source flow. |
| `source_flow_type` | string | No | The type of flow that originated the ReceivedCredit (for example, `outbound_payment`). |

