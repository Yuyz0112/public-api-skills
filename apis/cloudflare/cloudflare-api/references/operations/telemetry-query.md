# POST /accounts/{account_id}/workers/observability/telemetry/query

**Resource:** [Query run](../resources/Query-run.md)
**Run a query**
**Operation ID:** `telemetry.query`

Runs a temporary or saved query

## Request Body

Query your observability events, requests, and traces. Build visualizations and identify insights.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful request |
| 400 | Bad Request |
| 401 | Unauthorized |
| 500 | Internal error |

