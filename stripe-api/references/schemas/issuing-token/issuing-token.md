# issuing.token

An issuing token object is created when an issued card is added to a digital wallet. As a [card issuer](https://docs.stripe.com/issuing), you can [view and manage these tokens](https://docs.stripe.com/issuing/controls/token-management) through Stripe.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card` | any | Yes | Card associated with this token. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `device_fingerprint` | string | No | The hashed ID derived from the device ID from the card network associated with the token. |
| `id` | string | Yes | Unique identifier for the object. |
| `last4` | string | No | The last four digits of the token. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `network` | enum: mastercard, visa | Yes | The token service provider / card network associated with the token. |
| `network_data` | [issuing_network_token_network_data](issuing-network-token-network-data.md) | No |  |
| `network_updated_at` | integer (unix-time) | Yes | Time at which the token was last updated by the card network. Measured in seconds since the Unix epoch. |
| `object` | enum: issuing.token | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, deleted, requested... | Yes | The usage state of the token. |
| `wallet_provider` | enum: apple_pay, google_pay, samsung_pay | No | The digital wallet for this token, if one was used. |

