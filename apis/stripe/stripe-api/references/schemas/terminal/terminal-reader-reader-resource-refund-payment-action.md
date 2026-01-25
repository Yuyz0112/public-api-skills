# terminal_reader_reader_resource_refund_payment_action

Represents a reader action to refund a payment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | The amount being refunded. |
| `charge` | any | No | Charge that is being refunded. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `payment_intent` | any | No | Payment intent that is being refunded. |
| `reason` | enum: duplicate, fraudulent, requested_by_customer | No | The reason for the refund. |
| `refund` | any | No | Unique identifier for the refund object. |
| `refund_application_fee` | boolean | No | Boolean indicating whether the application fee should be refunded when refunding this charge. If a full charge refund is given, the full application fee will be refunded. Otherwise, the application fee will be refunded in an amount proportional to the amount of the charge refunded. An application fee can be refunded only by the application that created the charge. |
| `refund_payment_config` | [terminal_reader_reader_resource_refund_payment_config](terminal-reader-reader-resource-refund-payment-config.md) | No |  |
| `reverse_transfer` | boolean | No | Boolean indicating whether the transfer should be reversed when refunding this charge. The transfer will be reversed proportionally to the amount being refunded (either the entire or partial amount). A transfer can be reversed only by the application that created the charge. |

