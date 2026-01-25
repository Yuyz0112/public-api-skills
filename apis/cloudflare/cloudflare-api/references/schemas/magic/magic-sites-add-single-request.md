# magic_sites_add_single_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connector_id` | [magic_connector-id](magic-connector-id.md) | No |  |
| `description` | string | No |  |
| `ha_mode` | boolean | No | Site high availability mode. If set to true, the site can have two connectors and runs in high availability mode. |
| `location` | [magic_site-location](magic-site-location.md) | No |  |
| `name` | [magic_site-name](magic-site-name.md) | Yes |  |
| `secondary_connector_id` | [magic_secondary-connector-id](magic-secondary-connector-id.md) | No |  |

