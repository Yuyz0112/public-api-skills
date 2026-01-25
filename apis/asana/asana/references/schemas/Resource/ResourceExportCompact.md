# ResourceExportCompact

A *resource_export* object represents a request to bulk export objects for one or more resources.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `created_at` | string (date-time) | No | The time at which the resource export object was created. |
| `download_url` | string (uri) | No | Download this URL to retrieve the full export
in [JSON Lines](https://jsonlines.org/) format. It will be compressed in a gzip (.gz) container.

*Note: May be null if the export is still in progress or failed.* |
| `completed_at` | string (date-time) | No | The time at which this resource was completed. This will be null if the export is still in progress. |

