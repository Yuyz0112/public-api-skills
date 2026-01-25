# migration

A migration.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `owner` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `guid` | string | Yes |  |
| `state` | string | Yes |  |
| `lock_repositories` | boolean | Yes |  |
| `exclude_metadata` | boolean | Yes |  |
| `exclude_git_data` | boolean | Yes |  |
| `exclude_attachments` | boolean | Yes |  |
| `exclude_releases` | boolean | Yes |  |
| `exclude_owner_projects` | boolean | Yes |  |
| `org_metadata_only` | boolean | Yes |  |
| `repositories` | repository[] | Yes | The repositories included in the migration. Only returned for export migrations. |
| `url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `node_id` | string | Yes |  |
| `archive_url` | string (uri) | No |  |
| `exclude` | string[] | No | Exclude related items from being returned in the response in order to improve performance of the request. The array can include any of: `"repositories"`. |

