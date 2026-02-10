# DELETE /api/v4/runners/managers

**Resource:** [CI runners](../resources/CI-runners.md)
**Delete a registered runner manager**
**Operation ID:** `deleteApiV4RunnersManagers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | The runner's authentication token |
| `system_id` | query | string | Yes | The runner's system identifier. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Runner manager was deleted |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |

