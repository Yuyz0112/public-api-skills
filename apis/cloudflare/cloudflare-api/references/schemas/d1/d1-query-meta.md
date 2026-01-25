# d1_query-meta

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `changed_db` | boolean | No | Denotes if the database has been altered in some way, like deleting rows. |
| `changes` | number | No | Rough indication of how many rows were modified by the query, as provided by SQLite's `sqlite3_total_changes()`. |
| `duration` | number | No | The duration of the SQL query execution inside the database. Does not include any network communication. |
| `last_row_id` | number | No | The row ID of the last inserted row in a table with an `INTEGER PRIMARY KEY` as provided by SQLite. Tables created with `WITHOUT ROWID` do not populate this. |
| `rows_read` | number | No | Number of rows read during the SQL query execution, including indices (not all rows are necessarily returned). |
| `rows_written` | number | No | Number of rows written during the SQL query execution, including indices. |
| `served_by_colo` | [d1_served-by-colo](d1-served-by-colo.md) | No |  |
| `served_by_primary` | boolean | No | Denotes if the query has been handled by the database primary instance. |
| `served_by_region` | [d1_served-by-region](d1-served-by-region.md) | No |  |
| `size_after` | number | No | Size of the database after the query committed, in bytes. |
| `timings` | object | No | Various durations for the query. |

## Nested Fields

### `timings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sql_duration_ms` | number | No | The duration of the SQL query execution inside the database. Does not include any network communication. |

