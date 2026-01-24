# source_receiver_flow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | string | No | The address of the receiver source. This is the value that should be communicated to the customer to send their funds to. |
| `amount_charged` | integer | Yes | The total amount that was moved to your balance. This is almost always equal to the amount charged. In rare cases when customers deposit excess funds and we are unable to refund those, those funds get moved to your balance and show up in amount_charged as well. The amount charged is expressed in the source's currency. |
| `amount_received` | integer | Yes | The total amount received by the receiver source. `amount_received = amount_returned + amount_charged` should be true for consumed sources unless customers deposit excess funds. The amount received is expressed in the source's currency. |
| `amount_returned` | integer | Yes | The total amount that was returned to the customer. The amount returned is expressed in the source's currency. |
| `refund_attributes_method` | string | Yes | Type of refund attribute method, one of `email`, `manual`, or `none`. |
| `refund_attributes_status` | string | Yes | Type of refund attribute status, one of `missing`, `requested`, or `available`. |

