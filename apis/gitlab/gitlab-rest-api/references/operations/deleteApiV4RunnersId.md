# DELETE /api/v4/runners/{id}

**Resource:** [Runners](../resources/Runners.md)
**Remove a runner**
**Operation ID:** `deleteApiV4RunnersId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a runner |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Runner associated with more than one project |
| 404 | Runner not found |
| 412 | Precondition Failed |

