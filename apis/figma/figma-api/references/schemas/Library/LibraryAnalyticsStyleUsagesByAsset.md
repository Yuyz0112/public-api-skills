# LibraryAnalyticsStyleUsagesByAsset

Library analytics style usage data broken down by component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `style_key` | string | Yes | Unique, stable id of the style. |
| `style_name` | string | Yes | The name of the style. |
| `style_type` | string | Yes | The type of the style. |
| `usages` | number | Yes | The number of usages of the style within the organization. |
| `teams_using` | number | Yes | The number of teams using the style within the organization. |
| `files_using` | number | Yes | The number of files using the style within the organization. |

