# DELETE /api/v4/projects/{id}/runners/{runner_id}

**Resource:** [Runners](../resources/Runners.md)
**Unassign a runner from project**
**Operation ID:** `deleteApiV4ProjectsIdRunnersRunnerId`

It is not possible to unassign a runner from the owner project. If so, an error is returned. Use the call to delete a runner instead.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `runner_id` | path | integer | Yes | The ID of a runner |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 403 | You cannot unassign a runner from the owner project. Delete the runner instead |
| 404 | Runner not found |
| 412 | Precondition Failed |

