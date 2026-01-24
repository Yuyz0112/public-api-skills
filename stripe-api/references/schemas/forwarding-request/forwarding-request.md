# forwarding.request

Instructs Stripe to make a request on your behalf using the destination URL. The destination URL
is activated by Stripe at the time of onboarding. Stripe verifies requests with your credentials
provided during onboarding, and injects card details from the payment_method into the request.

Stripe redacts all sensitive fields and headers, including authentication credentials and card numbers,
before storing the request and response data in the forwarding Request object, which are subject to a
30-day retention period.

You can provide a Stripe idempotency key to make sure that requests with the same key result in only one
outbound request. The Stripe idempotency key provided should be unique and different from any idempotency
keys provided on the underlying third-party request.

Forwarding Requests are synchronous requests that return a response or time out according to
Stripe’s limits.

Related guide: [Forward card details to third-party API endpoints](https://docs.stripe.com/payments/forwarding).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: forwarding.request | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payment_method` | string | Yes | The PaymentMethod to insert into the forwarded request. Forwarding previously consumed PaymentMethods is allowed. |
| `replacements` | string[] | Yes | The field kinds to be replaced in the forwarded request. |
| `request_context` | any | No | Context about the request from Stripe's servers to the destination endpoint. |
| `request_details` | any | No | The request that was sent to the destination endpoint. We redact any sensitive fields. |
| `response_details` | any | No | The response that the destination endpoint returned to us. We redact any sensitive fields. |
| `url` | string | No | The destination URL for the forwarded request. Must be supported by the config. |

