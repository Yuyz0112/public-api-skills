# LibraryAnalyticsComponentUsagesByAsset

Library analytics component usage data broken down by component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component_key` | string | Yes | Unique, stable id of the component. |
| `component_name` | string | Yes | Name of the component. |
| `component_set_key` | string | No | Unique, stable id of the component set that this component belongs to. |
| `component_set_name` | string | No | Name of the component set that this component belongs to. |
| `usages` | number | Yes | The number of instances of the component within the organization. |
| `teams_using` | number | Yes | The number of teams using the component within the organization. |
| `files_using` | number | Yes | The number of files using the component within the organization. |

