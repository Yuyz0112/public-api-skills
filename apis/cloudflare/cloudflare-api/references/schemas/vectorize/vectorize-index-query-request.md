# vectorize_index-query-request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filter` | object | No | A metadata filter expression used to limit nearest neighbor results. |
| `returnMetadata` | boolean | No | Whether to return the metadata associated with the closest vectors. |
| `returnValues` | boolean | No | Whether to return the values associated with the closest vectors. |
| `topK` | number | No | The number of nearest neighbors to find. |
| `vector` | number[] | Yes | The search vector that will be used to find the nearest neighbors. |

