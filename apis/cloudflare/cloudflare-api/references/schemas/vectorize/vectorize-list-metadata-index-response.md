# vectorize_list-metadata-index-response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metadataIndexes` | object[] | No | Array of indexed metadata properties. |

## Nested Fields

### `metadataIndexes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `indexType` | enum: string, number, boolean | No | Specifies the type of indexed metadata property. |
| `propertyName` | string | No | Specifies the indexed metadata property. |

