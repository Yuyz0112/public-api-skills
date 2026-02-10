# PATCH /api/v4/namespaces/{id}/minutes/move/{target_id}

**Resource:** [CI minutes](../resources/CI-minutes.md)
**[DEPRECATED] Transfer purchased compute minutes packs to another namespace**
**Operation ID:** `patchApiV4NamespacesIdMinutesMoveTargetId`

Moves additional packs from one namespace to another

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the namespace to transfer from |
| `target_id` | path | string | Yes | The ID of the namespace for the packs to transfer to |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

