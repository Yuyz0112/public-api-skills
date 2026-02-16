# POST /index.php?/api/v2/add_result/{test_id}

**Resource:** [results](../resources/results.md)
**Add result for test**
**Operation ID:** `addResult`

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
