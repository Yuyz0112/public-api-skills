# GET /index.php?/api/v2/get_cases/{project_id}

**Resource:** [cases](../resources/cases.md)
**Get cases**
**Operation ID:** `getCases`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Case list |
| default | (reference) |

**Success Response Schema:**

[PaginatedCases](../schemas/Paginated/PaginatedCases.md)

## Security

- **basicAuth**
