# autolink

An autolink reference.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `key_prefix` | string | Yes | The prefix of a key that is linkified. |
| `url_template` | string | Yes | A template for the target URL that is generated if a key was found. |
| `is_alphanumeric` | boolean | Yes | Whether this autolink reference matches alphanumeric characters. If false, this autolink reference only matches numeric characters. |
| `updated_at` | string (date-time) | No |  |

