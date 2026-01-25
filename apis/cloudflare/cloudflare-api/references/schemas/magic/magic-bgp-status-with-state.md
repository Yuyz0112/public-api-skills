# magic_bgp_status_with_state

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bgp_state` | string | No |  |
| `cf_speaker_ip` | string (ipv4) | No |  |
| `cf_speaker_port` | integer | No |  |
| `customer_speaker_ip` | string (ipv4) | No |  |
| `customer_speaker_port` | integer | No |  |
| `state` | enum: BGP_DOWN, BGP_UP, BGP_ESTABLISHING | Yes |  |
| `tcp_established` | boolean | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

