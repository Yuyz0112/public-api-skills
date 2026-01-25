# teams-devices_cursor_result_info

V4 public API Pagination/Cursor info.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | Yes | Number of records in the response. |
| `cursor` | string | Yes | Opaque token to request the next set of records. |
| `per_page` | integer | Yes | The limit for the number of records in the response. |
| `total_count` | integer | No | Total number of records available. |

