# intel_schemas-ip

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `belongs_to_ref` | object | No | Specifies a reference to the autonomous systems (AS) that the IP address belongs to. |
| `ip` | [intel_ip](intel-ip.md) | No |  |
| `risk_types` | object[] | No |  |

## Nested Fields

### `belongs_to_ref`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country` | string | No |  |
| `description` | string | No |  |
| `id` | string | No |  |
| `type` | enum: hosting_provider, isp, organization | No | Infrastructure type of this ASN. |
| `value` | string | No |  |

### `risk_types`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | No |  |
| `name` | string | No |  |
| `super_category_id` | number | No |  |

