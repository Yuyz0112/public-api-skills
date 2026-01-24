# payment_method_details_wechat_pay

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fingerprint` | string | No | Uniquely identifies this particular WeChat Pay account. You can use this attribute to check whether two WeChat accounts are the same. |
| `location` | string | No | ID of the [location](https://docs.stripe.com/api/terminal/locations) that this transaction's reader is assigned to. |
| `reader` | string | No | ID of the [reader](https://docs.stripe.com/api/terminal/readers) this transaction was made on. |
| `transaction_id` | string | No | Transaction ID of this particular WeChat Pay transaction. |

