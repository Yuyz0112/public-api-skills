# POST /index.php?/api/v2/add_results/{run_id}

**Resource:** [results](../resources/results.md)
**Bulk add results by test_id**
**Operation ID:** `addResults`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddResultsRequest](../schemas/Add/AddResultsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Added results |
| default | (reference) |

**Success Response Schema:**

[BulkResultsResponse](../schemas/Bulk/BulkResultsResponse.md)

## Security

- **basicAuth**
