# codespace-export-details

An export of a codespace. Also, latest export details for a codespace can be fetched with id = latest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `state` | string | No | State of the latest export |
| `completed_at` | string (date-time) | No | Completion time of the last export operation |
| `branch` | string | No | Name of the exported branch |
| `sha` | string | No | Git commit SHA of the exported branch |
| `id` | string | No | Id for the export details |
| `export_url` | string | No | Url for fetching export details |
| `html_url` | string | No | Web url for the exported branch |

