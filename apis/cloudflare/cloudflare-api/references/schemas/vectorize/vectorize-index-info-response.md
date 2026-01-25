# vectorize_index-info-response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dimensions` | [vectorize_index-dimensions](vectorize-index-dimensions.md) | No |  |
| `processedUpToDatetime` | string (date-time) | No | Specifies the timestamp the last mutation batch was processed as an ISO8601 string. |
| `processedUpToMutation` | [vectorize_mutation-uuid](vectorize-mutation-uuid.md) | No |  |
| `vectorCount` | integer | No | Specifies the number of vectors present in the index |

