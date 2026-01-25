# ActivityLogFileRepoEntity

A file branch that diverges from and can be merged back into the main file

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: file_repo | Yes | The type of entity. |
| `id` | string | Yes | Unique identifier of the file branch. |
| `name` | string | Yes | Name of the file. |
| `main_file_key` | string | Yes | Key of the main file. |

