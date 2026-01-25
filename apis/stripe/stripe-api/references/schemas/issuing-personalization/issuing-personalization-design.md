# issuing.personalization_design

A Personalization Design is a logical grouping of a Physical Bundle, card logo, and carrier text that represents a product line.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_logo` | any | No | The file for the card logo to use with physical bundles that support card logos. Must have a `purpose` value of `issuing_logo`. |
| `carrier_text` | any | No | Hash containing carrier text, for use with physical bundles that support carrier text. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `lookup_key` | string | No | A lookup key used to retrieve personalization designs dynamically from a static string. This may be up to 200 characters. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | No | Friendly display name. |
| `object` | enum: issuing.personalization_design | Yes | String representing the object's type. Objects of the same type share the same value. |
| `physical_bundle` | any | Yes | The physical bundle object belonging to this personalization design. |
| `preferences` | [issuing_personalization_design_preferences](issuing-personalization-design-preferences.md) | Yes |  |
| `rejection_reasons` | [issuing_personalization_design_rejection_reasons](issuing-personalization-design-rejection-reasons.md) | Yes |  |
| `status` | enum: active, inactive, rejected... | Yes | Whether this personalization design can be used to create cards. |

