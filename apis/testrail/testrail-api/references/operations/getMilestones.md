# GET /index.php?/api/v2/get_milestones/{project_id}

**Resource:** [milestones](../resources/milestones.md)
**Get milestones**
**Operation ID:** `getMilestones`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Milestone list |
| default | (reference) |

**Success Response Schema:**

[PaginatedMilestones](../schemas/Paginated/PaginatedMilestones.md)

## Security

- **basicAuth**
