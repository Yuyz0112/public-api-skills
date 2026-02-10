# APIEntitiesBulkImportsEntity

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `bulk_import_id` | integer | No |  |
| `status` | string | No |  |
| `entity_type` | string | No |  |
| `source_full_path` | string | No |  |
| `destination_full_path` | string | No |  |
| `destination_name` | string | No |  |
| `destination_slug` | string | No |  |
| `destination_namespace` | string | No |  |
| `parent_id` | integer | No |  |
| `namespace_id` | integer | No |  |
| `project_id` | integer | No |  |
| `created_at` | DateTime | No |  |
| `updated_at` | DateTime | No |  |
| `failures` | APIEntitiesBulkImportsEntityFailure[] | No |  |
| `migrate_projects` | Boolean | No |  |
| `migrate_memberships` | Boolean | No |  |
| `has_failures` | Boolean | No |  |
| `stats` | object | No |  |

