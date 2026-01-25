# issuing.cardholder

An Issuing `Cardholder` object represents an individual or business entity who is [issued](https://docs.stripe.com/issuing) cards.

Related guide: [How to create a cardholder](https://docs.stripe.com/issuing/cards/virtual/issue-cards#create-cardholder)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing` | [issuing_cardholder_address](issuing-cardholder-address.md) | Yes |  |
| `company` | any | No | Additional information about a `company` cardholder. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `email` | string | No | The cardholder's email address. |
| `id` | string | Yes | Unique identifier for the object. |
| `individual` | any | No | Additional information about an `individual` cardholder. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | Yes | The cardholder's name. This will be printed on cards issued to them. |
| `object` | enum: issuing.cardholder | Yes | String representing the object's type. Objects of the same type share the same value. |
| `phone_number` | string | No | The cardholder's phone number. This is required for all cardholders who will be creating EU cards. See the [3D Secure documentation](https://docs.stripe.com/issuing/3d-secure#when-is-3d-secure-applied) for more details. |
| `preferred_locales` | string[] | No | The cardholder’s preferred locales (languages), ordered by preference. Locales can be `de`, `en`, `es`, `fr`, or `it`.
 This changes the language of the [3D Secure flow](https://docs.stripe.com/issuing/3d-secure) and one-time password messages sent to the cardholder. |
| `requirements` | [issuing_cardholder_requirements](issuing-cardholder-requirements.md) | Yes |  |
| `spending_controls` | any | No | Rules that control spending across this cardholder's cards. Refer to our [documentation](https://docs.stripe.com/issuing/controls/spending-controls) for more details. |
| `status` | enum: active, blocked, inactive | Yes | Specifies whether to permit authorizations on this cardholder's cards. |
| `type` | enum: company, individual | Yes | One of `individual` or `company`. See [Choose a cardholder type](https://docs.stripe.com/issuing/other/choose-cardholder) for more details. |

