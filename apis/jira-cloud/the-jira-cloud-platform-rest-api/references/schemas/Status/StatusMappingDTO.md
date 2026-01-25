# StatusMappingDTO

The mapping of old to new status ID for a specific project and issue type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueTypeId` | string | Yes | The issue type for the status mapping. |
| `projectId` | string | Yes | The project for the status mapping. |
| `statusMigrations` | StatusMigration[] | Yes | The list of old and new status ID mappings for the specified project and issue type. |

