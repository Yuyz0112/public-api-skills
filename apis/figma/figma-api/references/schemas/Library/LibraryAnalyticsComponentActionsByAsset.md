# LibraryAnalyticsComponentActionsByAsset

Library analytics component actions data broken down by asset.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `week` | string | Yes | The date in ISO 8601 format. e.g. 2023-12-13 |
| `component_key` | string | Yes | Unique, stable id of the component. |
| `component_name` | string | Yes | Name of the component. |
| `component_set_key` | string | No | Unique, stable id of the component set that this component belongs to. |
| `component_set_name` | string | No | Name of the component set that this component belongs to. |
| `detachments` | number | Yes | The number of detach events for this period. |
| `insertions` | number | Yes | The number of insertion events for this period. |

