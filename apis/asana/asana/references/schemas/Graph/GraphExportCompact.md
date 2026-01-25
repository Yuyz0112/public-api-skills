# GraphExportCompact

A *graph_export* object represents a request to export the data starting from a parent object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `created_at` | string (date-time) | No | The time at which this resource was created. |
| `download_url` | string (uri) | No | Download this URL to retrieve the full export
in JSON format. It will be compressed in a gzip (.gz) container.

*Note: May be null if the export is still in progress or
failed.  If present, this URL may only be valid for 1 hour from
the time of retrieval. You should avoid persisting this URL
somewhere and rather refresh on demand to ensure you do not keep
stale URLs.* |
| `completed_at` | string (date-time) | No | The time at which this resource was completed. |

