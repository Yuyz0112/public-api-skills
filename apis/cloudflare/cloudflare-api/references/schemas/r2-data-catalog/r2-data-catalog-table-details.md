# r2-data-catalog_table-details

Contains table with metadata.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | No | Indicates the creation timestamp in ISO 8601 format. |
| `identifier` | [r2-data-catalog_table-identifier](r2-data-catalog-table-identifier.md) | Yes |  |
| `location` | string | No | Specifies the base S3 URI for table storage location. |
| `metadata_location` | string | No | Contains the S3 URI to table metadata file. Null for staged tables. |
| `table_uuid` | string (uuid) | Yes | Contains the UUID that persists across renames. |
| `updated_at` | string (date-time) | No | Shows the last update timestamp in ISO 8601 format. Null if never updated. |

