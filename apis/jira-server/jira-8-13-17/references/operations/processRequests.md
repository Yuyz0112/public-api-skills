# POST /reindex/request

**Resource:** [reindex](../resources/reindex.md)
**Operation ID:** `processRequests`

Executes any pending reindex requests.  Returns a JSON array containing the IDs of the reindex requests
 that are being processed.  Execution is asynchronous - progress of the returned tasks can be monitored through
 other REST calls.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

