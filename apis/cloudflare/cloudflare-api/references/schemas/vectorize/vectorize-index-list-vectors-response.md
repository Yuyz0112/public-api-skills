# vectorize_index-list-vectors-response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | Yes | Number of vectors returned in this response |
| `cursorExpirationTimestamp` | string (date-time) | No | When the cursor expires as an ISO8601 string |
| `isTruncated` | boolean | Yes | Whether there are more vectors available beyond this response |
| `nextCursor` | string | No | Cursor for the next page of results |
| `totalCount` | integer | Yes | Total number of vectors in the index |
| `vectors` | vectorize_vector-list-item[] | Yes | Array of vector items |

