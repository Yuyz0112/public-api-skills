# organizations-api_Tenant

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cdate` | string (date-time) | Yes |  |
| `customer_id` | string | No |  |
| `edate` | string (date-time) | Yes |  |
| `tenant_contacts` | object | Yes |  |
| `tenant_labels` | string[] | Yes |  |
| `tenant_metadata` | object | Yes |  |
| `tenant_name` | string | Yes |  |
| `tenant_network` | object | Yes |  |
| `tenant_status` | string | Yes |  |
| `tenant_tag` | string | Yes |  |
| `tenant_type` | string | Yes |  |
| `tenant_units` | organizations-api_TenantUnit[] | Yes |  |

## Nested Fields

### `tenant_contacts`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email` | string | No |  |
| `website` | string | No |  |

### `tenant_metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dns` | object | No |  |

#### `tenant_metadata.dns`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ns_pool` | object | Yes |  |

