# radar.early_fraud_warning

An early fraud warning indicates that the card issuer has notified us that a
charge may be fraudulent.

Related guide: [Early fraud warnings](https://docs.stripe.com/disputes/measuring#early-fraud-warnings)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actionable` | boolean | Yes | An EFW is actionable if it has not received a dispute and has not been fully refunded. You may wish to proactively refund a charge that receives an EFW, in order to avoid receiving a dispute later. |
| `charge` | any | Yes | ID of the charge this early fraud warning is for, optionally expanded. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `fraud_type` | string | Yes | The type of fraud labelled by the issuer. One of `card_never_received`, `fraudulent_card_application`, `made_with_counterfeit_card`, `made_with_lost_card`, `made_with_stolen_card`, `misc`, `unauthorized_use_of_card`. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: radar.early_fraud_warning | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payment_intent` | any | No | ID of the Payment Intent this early fraud warning is for, optionally expanded. |

