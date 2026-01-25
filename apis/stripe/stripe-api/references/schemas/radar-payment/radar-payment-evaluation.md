# radar.payment_evaluation

Payment Evaluations represent the risk lifecycle of an externally processed payment. It includes the Radar risk score from Stripe, payment outcome taken by the merchant or processor, and any post transaction events, such as refunds or disputes. See the [Radar API guide](/radar/multiprocessor) for integration steps.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_device_metadata_details` | [insights_resources_payment_evaluation_client_device_metadata](insights-resources-payment-evaluation-client-device-metadata.md) | No |  |
| `created_at` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer_details` | [insights_resources_payment_evaluation_customer_details](insights-resources-payment-evaluation-customer-details.md) | No |  |
| `events` | insights_resources_payment_evaluation_event[] | Yes | Event information associated with the payment evaluation, such as refunds, dispute, early fraud warnings, or user interventions. |
| `id` | string | Yes | Unique identifier for the object. |
| `insights` | [insights_resources_payment_evaluation_insights](insights-resources-payment-evaluation-insights.md) | Yes |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: radar.payment_evaluation | Yes | String representing the object's type. Objects of the same type share the same value. |
| `outcome` | any | No | Indicates the final outcome for the payment evaluation. |
| `payment_details` | [insights_resources_payment_evaluation_payment_details](insights-resources-payment-evaluation-payment-details.md) | No |  |

