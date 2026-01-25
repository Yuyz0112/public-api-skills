# vectorize_index-query-v2-request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filter` | object | No | A metadata filter expression used to limit nearest neighbor results. |
| `returnMetadata` | enum: none, indexed, all | No | Whether to return no metadata, indexed metadata or all metadata associated with the closest vectors. |
| `returnValues` | boolean | No | Whether to return the values associated with the closest vectors. |
| `topK` | number | No | The number of nearest neighbors to find. |
| `vector` | number[] | Yes | The search vector that will be used to find the nearest neighbors. |

