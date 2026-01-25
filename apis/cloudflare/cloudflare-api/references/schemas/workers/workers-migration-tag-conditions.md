# workers_migration_tag_conditions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `new_tag` | string | No | Tag to set as the latest migration tag. |
| `old_tag` | string | No | Tag used to verify against the latest migration tag for this Worker. If they don't match, the upload is rejected. |

