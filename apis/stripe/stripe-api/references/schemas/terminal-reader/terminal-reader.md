# terminal.reader

A Reader represents a physical device for accepting payment details.

Related guide: [Connecting to a reader](https://docs.stripe.com/terminal/payments/connect-reader)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | any | No | The most recent action performed by the reader. |
| `device_sw_version` | string | No | The current software version of the reader. |
| `device_type` | enum: bbpos_chipper2x, bbpos_wisepad3, bbpos_wisepos_e... | Yes | Device type of the reader. |
| `id` | string | Yes | Unique identifier for the object. |
| `ip_address` | string | No | The local IP address of the reader. |
| `label` | string | Yes | Custom label given to the reader for easier identification. |
| `last_seen_at` | integer (unix-time) | No | The last time this reader reported to Stripe backend. Timestamp is measured in milliseconds since the Unix epoch. Unlike most other Stripe timestamp fields which use seconds, this field uses milliseconds. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `location` | any | No | The location identifier of the reader. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: terminal.reader | Yes | String representing the object's type. Objects of the same type share the same value. |
| `serial_number` | string | Yes | Serial number of the reader. |
| `status` | enum: offline, online | No | The networking status of the reader. We do not recommend using this field in flows that may block taking payments. |

