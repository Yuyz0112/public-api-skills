# vectorize_index-query-response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | No | Specifies the count of vectors returned by the search |
| `matches` | object[] | No | Array of vectors matched by the search |

## Nested Fields

### `matches`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [vectorize_vector-identifier](vectorize-vector-identifier.md) | No |  |
| `metadata` | object | No |  |
| `score` | number | No | The score of the vector according to the index's distance metric |
| `values` | number[] | No |  |

