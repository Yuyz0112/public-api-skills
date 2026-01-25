# CursorPagination

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `limit` | integer | Yes | The minimum of the `limit` parameter used in the request or the maximum request size of the API. |
| `next_cursor` | string | Yes | An opaque string than will deliver the next set of results when provided as the `cursor` parameter in a subsequent request.  A `null` value for this field indicates that there are no additional results.
 |

