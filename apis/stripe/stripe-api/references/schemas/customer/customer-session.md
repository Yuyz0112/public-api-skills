# customer_session

A Customer Session allows you to grant Stripe's frontend SDKs (like Stripe.js) client-side access
control over a Customer.

Related guides: [Customer Session with the Payment Element](/payments/accept-a-payment-deferred?platform=web&type=payment#save-payment-methods),
[Customer Session with the Pricing Table](/payments/checkout/pricing-table#customer-session),
[Customer Session with the Buy Button](/payment-links/buy-button#pass-an-existing-customer).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_secret` | string | Yes | The client secret of this Customer Session. Used on the client to set up secure access to the given `customer`.

The client secret can be used to provide access to `customer` from your frontend. It should not be stored, logged, or exposed to anyone other than the relevant customer. Make sure that you have TLS enabled on any page that includes the client secret. |
| `components` | [customer_session_resource_components](customer-session-resource-components.md) | No |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer` | any | Yes | The Customer the Customer Session was created for. |
| `customer_account` | string | No | The Account that the Customer Session was created for. |
| `expires_at` | integer (unix-time) | Yes | The timestamp at which this Customer Session will expire. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: customer_session | Yes | String representing the object's type. Objects of the same type share the same value. |

