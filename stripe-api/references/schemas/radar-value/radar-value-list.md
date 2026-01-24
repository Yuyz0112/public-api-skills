# radar.value_list

Value lists allow you to group values together which can then be referenced in rules.

Related guide: [Default Stripe lists](https://docs.stripe.com/radar/lists#managing-list-items)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alias` | string | Yes | The name of the value list for use in rules. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `created_by` | string | Yes | The name or email address of the user who created this value list. |
| `id` | string | Yes | Unique identifier for the object. |
| `item_type` | enum: card_bin, card_fingerprint, case_sensitive_string... | Yes | The type of items in the value list. One of `card_fingerprint`, `card_bin`, `email`, `ip_address`, `country`, `string`, `case_sensitive_string`, `customer_id`, `sepa_debit_fingerprint`, or `us_bank_account_fingerprint`. |
| `list_items` | object | Yes | List of items contained within this value list. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | Yes | The name of the value list. |
| `object` | enum: radar.value_list | Yes | String representing the object's type. Objects of the same type share the same value. |

## Nested Fields

### `list_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | radar.value_list_item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

