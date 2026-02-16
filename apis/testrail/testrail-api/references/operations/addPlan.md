# POST /index.php?/api/v2/add_plan/{project_id}

**Resource:** [plans](../resources/plans.md)
**Add plan**
**Operation ID:** `addPlan`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddPlanRequest](../schemas/Add/AddPlanRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Created plan |
| default | (reference) |

**Success Response Schema:**

[Plan](../schemas/Plan/Plan.md)

## Security

- **basicAuth**
