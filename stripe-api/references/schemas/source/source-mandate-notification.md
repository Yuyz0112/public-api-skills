# source_mandate_notification

Source mandate notifications should be created when a notification related to
a source mandate must be sent to the payer. They will trigger a webhook or
deliver an email to the customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acss_debit` | [source_mandate_notification_acss_debit_data](source-mandate-notification-acss-debit-data.md) | No |  |
| `amount` | integer | No | A positive integer in the smallest currency unit (that is, 100 cents for $1.00, or 1 for ¥1, Japanese Yen being a zero-decimal currency) representing the amount associated with the mandate notification. The amount is expressed in the currency of the underlying source. Required if the notification type is `debit_initiated`. |
| `bacs_debit` | [source_mandate_notification_bacs_debit_data](source-mandate-notification-bacs-debit-data.md) | No |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: source_mandate_notification | Yes | String representing the object's type. Objects of the same type share the same value. |
| `reason` | string | Yes | The reason of the mandate notification. Valid reasons are `mandate_confirmed` or `debit_initiated`. |
| `sepa_debit` | [source_mandate_notification_sepa_debit_data](source-mandate-notification-sepa-debit-data.md) | No |  |
| `source` | [source](source.md) | Yes |  |
| `status` | string | Yes | The status of the mandate notification. Valid statuses are `pending` or `submitted`. |
| `type` | string | Yes | The type of source this mandate notification is attached to. Should be the source type identifier code for the payment method, such as `three_d_secure`. |

