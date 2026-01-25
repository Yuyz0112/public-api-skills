# file_link

To share the contents of a `File` object with non-Stripe users, you can
create a `FileLink`. `FileLink`s contain a URL that you can use to
retrieve the contents of the file without authentication.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `expired` | boolean | Yes | Returns if the link is already expired. |
| `expires_at` | integer (unix-time) | No | Time that the link expires. |
| `file` | any | Yes | The file object this link points to. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: file_link | Yes | String representing the object's type. Objects of the same type share the same value. |
| `url` | string | No | The publicly accessible URL to download the file. |

