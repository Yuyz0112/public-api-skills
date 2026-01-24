# payment_intents

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/payment_intents` | List all PaymentIntents | [View](../operations/getpaymentintents.md) |
| POST | `/v1/payment_intents` | Create a PaymentIntent | [View](../operations/postpaymentintents.md) |
| GET | `/v1/payment_intents/search` | Search PaymentIntents | [View](../operations/getpaymentintentssearch.md) |
| GET | `/v1/payment_intents/{intent}` | Retrieve a PaymentIntent | [View](../operations/getpaymentintentsintent.md) |
| POST | `/v1/payment_intents/{intent}` | Update a PaymentIntent | [View](../operations/postpaymentintentsintent.md) |
| GET | `/v1/payment_intents/{intent}/amount_details_line_items` | List all PaymentIntent LineItems | [View](../operations/getpaymentintentsintentamountdetailslineitems.md) |
| POST | `/v1/payment_intents/{intent}/apply_customer_balance` | Reconcile a customer_balance PaymentIntent | [View](../operations/postpaymentintentsintentapplycustomerbalance.md) |
| POST | `/v1/payment_intents/{intent}/cancel` | Cancel a PaymentIntent | [View](../operations/postpaymentintentsintentcancel.md) |
| POST | `/v1/payment_intents/{intent}/capture` | Capture a PaymentIntent | [View](../operations/postpaymentintentsintentcapture.md) |
| POST | `/v1/payment_intents/{intent}/confirm` | Confirm a PaymentIntent | [View](../operations/postpaymentintentsintentconfirm.md) |
| POST | `/v1/payment_intents/{intent}/increment_authorization` | Increment an authorization | [View](../operations/postpaymentintentsintentincrementauthorization.md) |
| POST | `/v1/payment_intents/{intent}/verify_microdeposits` | Verify microdeposits on a PaymentIntent | [View](../operations/postpaymentintentsintentverifymicrodeposits.md) |
