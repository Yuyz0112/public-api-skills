# DELETE /api/v4/projects/{id}/triggers/{trigger_id}

**Resource:** [CI triggers](../resources/CI-triggers.md)
**Delete a trigger token**
**Operation ID:** `deleteApiV4ProjectsIdTriggersTriggerId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `trigger_id` | path | integer | Yes | The trigger token ID |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 412 | Precondition Failed |

