# GET /index.php?/api/v2/get_plans/{project_id}

**Resource:** [plans](../resources/plans.md)
**Get plans**
**Operation ID:** `getPlans`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Plan list |
| default | (reference) |

**Success Response Schema:**

[PaginatedPlans](../schemas/Paginated/PaginatedPlans.md)

## Security

- **basicAuth**
