# diff-entry

Diff Entry

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `filename` | string | Yes |  |
| `status` | enum: added, removed, modified... | Yes |  |
| `additions` | integer | Yes |  |
| `deletions` | integer | Yes |  |
| `changes` | integer | Yes |  |
| `blob_url` | string (uri) | Yes |  |
| `raw_url` | string (uri) | Yes |  |
| `contents_url` | string (uri) | Yes |  |
| `patch` | string | No |  |
| `previous_filename` | string | No |  |

