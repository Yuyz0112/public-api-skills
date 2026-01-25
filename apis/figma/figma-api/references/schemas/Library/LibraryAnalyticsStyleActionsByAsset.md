# LibraryAnalyticsStyleActionsByAsset

Library analytics style actions data broken down by asset.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `week` | string | Yes | The date in ISO 8601 format. e.g. 2023-12-13 |
| `style_key` | string | Yes | Unique, stable id of the style. |
| `style_name` | string | Yes | The name of the style. |
| `style_type` | string | Yes | The type of the style. |
| `detachments` | number | Yes | The number of detach events for this period. |
| `insertions` | number | Yes | The number of insertion events for this period. |

