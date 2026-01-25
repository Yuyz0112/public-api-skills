# payment_intents

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/payment_intents` | List all PaymentIntents | [View](../operations/GetPaymentIntents.md) |
| POST | `/v1/payment_intents` | Create a PaymentIntent | [View](../operations/PostPaymentIntents.md) |
| GET | `/v1/payment_intents/search` | Search PaymentIntents | [View](../operations/GetPaymentIntentsSearch.md) |
| GET | `/v1/payment_intents/{intent}` | Retrieve a PaymentIntent | [View](../operations/GetPaymentIntentsIntent.md) |
| POST | `/v1/payment_intents/{intent}` | Update a PaymentIntent | [View](../operations/PostPaymentIntentsIntent.md) |
| GET | `/v1/payment_intents/{intent}/amount_details_line_items` | List all PaymentIntent LineItems | [View](../operations/GetPaymentIntentsIntentAmountDetailsLineItems.md) |
| POST | `/v1/payment_intents/{intent}/apply_customer_balance` | Reconcile a customer_balance PaymentIntent | [View](../operations/PostPaymentIntentsIntentApplyCustomerBalance.md) |
| POST | `/v1/payment_intents/{intent}/cancel` | Cancel a PaymentIntent | [View](../operations/PostPaymentIntentsIntentCancel.md) |
| POST | `/v1/payment_intents/{intent}/capture` | Capture a PaymentIntent | [View](../operations/PostPaymentIntentsIntentCapture.md) |
| POST | `/v1/payment_intents/{intent}/confirm` | Confirm a PaymentIntent | [View](../operations/PostPaymentIntentsIntentConfirm.md) |
| POST | `/v1/payment_intents/{intent}/increment_authorization` | Increment an authorization | [View](../operations/PostPaymentIntentsIntentIncrementAuthorization.md) |
| POST | `/v1/payment_intents/{intent}/verify_microdeposits` | Verify microdeposits on a PaymentIntent | [View](../operations/PostPaymentIntentsIntentVerifyMicrodeposits.md) |
