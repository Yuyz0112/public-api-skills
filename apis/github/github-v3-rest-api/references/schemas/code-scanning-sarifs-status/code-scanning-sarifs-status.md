# code-scanning-sarifs-status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `processing_status` | enum: pending, complete, failed | No | `pending` files have not yet been processed, while `complete` means results from the SARIF have been stored. `failed` files have either not been processed at all, or could only be partially processed. |
| `analyses_url` | string (uri) | No | The REST API URL for getting the analyses associated with the upload. |
| `errors` | string[] | No | Any errors that ocurred during processing of the delivery. |

