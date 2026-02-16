# GET /index.php?/api/v2/get_results_for_case/{run_id}/{case_id}

**Resource:** [results](../resources/results.md)
**Get results for run/case**
**Operation ID:** `getResultsForCase`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Result list |
| default | (reference) |

**Success Response Schema:**

[PaginatedResults](../schemas/Paginated/PaginatedResults.md)

## Security

- **basicAuth**
