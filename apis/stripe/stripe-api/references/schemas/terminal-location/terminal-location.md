# terminal.location

A Location represents a grouping of readers.

Related guide: [Fleet management](https://docs.stripe.com/terminal/fleet/locations)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | [address](address.md) | Yes |  |
| `address_kana` | [legal_entity_japan_address](legal-entity-japan-address.md) | No |  |
| `address_kanji` | [legal_entity_japan_address](legal-entity-japan-address.md) | No |  |
| `configuration_overrides` | string | No | The ID of a configuration that will be used to customize all readers in this location. |
| `display_name` | string | Yes | The display name of the location. |
| `display_name_kana` | string | No | The Kana variation of the display name of the location. |
| `display_name_kanji` | string | No | The Kanji variation of the display name of the location. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: terminal.location | Yes | String representing the object's type. Objects of the same type share the same value. |
| `phone` | string | No | The phone number of the location. |

