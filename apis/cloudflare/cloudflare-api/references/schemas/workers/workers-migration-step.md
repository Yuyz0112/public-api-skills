# workers_migration_step

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deleted_classes` | string[] | No | A list of classes to delete Durable Object namespaces from. |
| `new_classes` | string[] | No | A list of classes to create Durable Object namespaces from. |
| `new_sqlite_classes` | string[] | No | A list of classes to create Durable Object namespaces with SQLite from. |
| `renamed_classes` | object[] | No | A list of classes with Durable Object namespaces that were renamed. |
| `transferred_classes` | object[] | No | A list of transfers for Durable Object namespaces from a different Worker and class to a class defined in this Worker. |

## Nested Fields

### `renamed_classes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

### `transferred_classes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `from_script` | string | No |  |
| `to` | string | No |  |

