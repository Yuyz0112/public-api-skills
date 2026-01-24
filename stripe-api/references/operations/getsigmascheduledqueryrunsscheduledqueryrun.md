# GET /v1/sigma/scheduled_query_runs/{scheduled_query_run}

**Resource:** [sigma](../resources/sigma.md)
**Retrieve a scheduled query run**
**Operation ID:** `GetSigmaScheduledQueryRunsScheduledQueryRun`

<p>Retrieves the details of an scheduled query run.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `scheduled_query_run` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[scheduled_query_run](../schemas/scheduled/scheduled-query-run.md)

