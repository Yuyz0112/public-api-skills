# POST /index.php?/api/v2/add_results_for_cases/{run_id}

**Resource:** [results](../resources/results.md)
**Bulk add results by case_id**
**Operation ID:** `addResultsForCases`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddResultsForCasesRequest](../schemas/Add/AddResultsForCasesRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Added results |
| default | (reference) |

**Success Response Schema:**

[BulkResultsResponse](../schemas/Bulk/BulkResultsResponse.md)

## Security

- **basicAuth**
