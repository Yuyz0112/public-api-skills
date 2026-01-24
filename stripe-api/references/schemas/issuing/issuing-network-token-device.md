# issuing_network_token_device

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `device_fingerprint` | string | No | An obfuscated ID derived from the device ID. |
| `ip_address` | string | No | The IP address of the device at provisioning time. |
| `location` | string | No | The geographic latitude/longitude coordinates of the device at provisioning time. The format is [+-]decimal/[+-]decimal. |
| `name` | string | No | The name of the device used for tokenization. |
| `phone_number` | string | No | The phone number of the device used for tokenization. |
| `type` | enum: other, phone, watch | No | The type of device used for tokenization. |

