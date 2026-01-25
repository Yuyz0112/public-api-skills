# pages_domain

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `certificate_authority` | enum: google, lets_encrypt | Yes |  |
| `created_on` | string | Yes |  |
| `domain_id` | string | Yes |  |
| `id` | string | Yes |  |
| `name` | [pages_domain_name](pages-domain-name.md) | Yes |  |
| `status` | enum: initializing, pending, active... | Yes |  |
| `validation_data` | object | Yes |  |
| `verification_data` | object | Yes |  |
| `zone_tag` | string | Yes |  |

## Nested Fields

### `validation_data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error_message` | string | No |  |
| `method` | enum: http, txt | Yes |  |
| `status` | enum: initializing, pending, active... | Yes |  |
| `txt_name` | string | No |  |
| `txt_value` | string | No |  |

### `verification_data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error_message` | string | No |  |
| `status` | enum: pending, active, deactivated... | Yes |  |

