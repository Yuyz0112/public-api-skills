# POST /index.php?/api/v2/add_result_for_case/{run_id}/{case_id}

**Resource:** [results](../resources/results.md)
**Add result for run/case**
**Operation ID:** `addResultForCase`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddResultRequest](../schemas/Add/AddResultRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Added result |
| default | (reference) |

**Success Response Schema:**

[Result](../schemas/Result/Result.md)

## Security

- **basicAuth**
