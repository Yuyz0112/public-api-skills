# balance

This is an object representing your Stripe balance. You can retrieve it to see
the balance currently on your Stripe account.

The top-level `available` and `pending` comprise your "payments balance."

Related guide: [Balances and settlement time](https://docs.stripe.com/payments/balances), [Understanding Connect account balances](https://docs.stripe.com/connect/account-balances)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `available` | balance_amount[] | Yes | Available funds that you can transfer or pay out automatically by Stripe or explicitly through the [Transfers API](https://api.stripe.com#transfers) or [Payouts API](https://api.stripe.com#payouts). You can find the available balance for each currency and payment type in the `source_types` property. |
| `connect_reserved` | balance_amount[] | No | Funds held due to negative balances on connected accounts where [account.controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `application`, which includes Custom accounts. You can find the connect reserve balance for each currency and payment type in the `source_types` property. |
| `instant_available` | balance_amount_net[] | No | Funds that you can pay out using Instant Payouts. |
| `issuing` | [balance_detail](balance-detail.md) | No |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: balance | Yes | String representing the object's type. Objects of the same type share the same value. |
| `pending` | balance_amount[] | Yes | Funds that aren't available in the balance yet. You can find the pending balance for each currency and each payment type in the `source_types` property. |
| `refund_and_dispute_prefunding` | [balance_detail_ungated](balance-detail-ungated.md) | No |  |

