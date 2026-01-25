# magic-visibility-mnm_mnm_config_warp_device

Object representing a warp device with an ID and name.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Unique identifier for the warp device. |
| `name` | string | Yes | Name of the warp device. |
| `router_ip` | string | Yes | IPv4 CIDR of the router sourcing flow data associated with this warp device. Only /32 addresses are currently supported. |

