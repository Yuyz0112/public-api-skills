# payment_method_naver_pay

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `buyer_id` | string | No | Uniquely identifies this particular Naver Pay account. You can use this attribute to check whether two Naver Pay accounts are the same. |
| `funding` | enum: card, points | Yes | Whether to fund this transaction with Naver Pay points or a card. |

