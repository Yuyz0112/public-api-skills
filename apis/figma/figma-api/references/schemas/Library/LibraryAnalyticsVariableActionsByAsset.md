# LibraryAnalyticsVariableActionsByAsset

Library analytics variable actions data broken down by asset.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `week` | string | Yes | The date in ISO 8601 format. e.g. 2023-12-13 |
| `variable_key` | string | Yes | Unique, stable id of the variable. |
| `variable_name` | string | Yes | The name of the variable. |
| `variable_type` | string | Yes | The type of the variable. |
| `collection_key` | string | Yes | Unique, stable id of the collection the variable belongs to. |
| `collection_name` | string | Yes | The name of the collection the variable belongs to. |
| `detachments` | number | Yes | The number of detach events for this period. |
| `insertions` | number | Yes | The number of insertion events for this period. |

