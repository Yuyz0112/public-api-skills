# teams-devices_fallback_domain

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | A description of the fallback domain, displayed in the client UI. |
| `dns_server` | teams-devices_ip[] | No | A list of IP addresses to handle domain resolution. |
| `suffix` | string | Yes | The domain suffix to match when resolving locally. |

