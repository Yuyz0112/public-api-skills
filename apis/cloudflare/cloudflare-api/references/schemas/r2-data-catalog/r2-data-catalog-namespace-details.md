# r2-data-catalog_namespace-details

Contains namespace with metadata details.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | Indicates the creation timestamp in ISO 8601 format. |
| `namespace` | [r2-data-catalog_namespace-identifier](r2-data-catalog-namespace-identifier.md) | Yes |  |
| `namespace_uuid` | string (uuid) | Yes | Contains the UUID that persists across renames. |
| `updated_at` | string (date-time) | No | Shows the last update timestamp in ISO 8601 format. Null if never updated. |

