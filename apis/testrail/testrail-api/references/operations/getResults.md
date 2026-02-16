# GET /index.php?/api/v2/get_results/{test_id}

**Resource:** [results](../resources/results.md)
**Get results for test**
**Operation ID:** `getResults`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Result list |
| default | (reference) |

**Success Response Schema:**

[PaginatedResults](../schemas/Paginated/PaginatedResults.md)

## Security

- **basicAuth**
