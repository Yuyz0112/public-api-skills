# GET /reindex/request/bulk

**Resource:** [reindex](../resources/reindex.md)
**Operation ID:** `getProgressBulk`

Retrieves the progress of a multiple reindex requests.  Only reindex requests that actually exist will be returned
 in the results.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `requestId` | query | string | No | the reindex request IDs. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

