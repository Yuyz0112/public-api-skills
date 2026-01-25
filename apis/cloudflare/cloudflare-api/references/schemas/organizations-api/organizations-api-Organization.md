# organizations-api_Organization

References an Organization in the Cloudflare data model.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `create_time` | string (date-time) | Yes |  |
| `id` | any | Yes |  |
| `meta` | object | Yes |  |
| `name` | string | Yes |  |
| `parent` | object | No |  |
| `profile` | [organizations-api_Profile](organizations-api-Profile.md) | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `flags` | any | No |  |
| `managed_by` | string | No |  |

### `parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [organizations-api_OrganizationID](organizations-api-OrganizationID.md) | Yes |  |
| `name` | string | Yes |  |

