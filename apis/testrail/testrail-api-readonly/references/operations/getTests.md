# GET /index.php?/api/v2/get_tests/{run_id}

**Resource:** [read](../resources/read.md)
**Get tests in run**
**Operation ID:** `getTests`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Test list |
| default | (reference) |

**Success Response Schema:**

[PaginatedTests](../schemas/Paginated/PaginatedTests.md)

## Security

- **basicAuth**
