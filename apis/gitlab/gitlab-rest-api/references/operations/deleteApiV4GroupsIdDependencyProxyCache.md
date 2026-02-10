# DELETE /api/v4/groups/{id}/dependency_proxy/cache

**Resource:** [Dependency proxy](../resources/Dependency-proxy.md)
**Purge the dependency proxy for a group**
**Operation ID:** `deleteApiV4GroupsIdDependencyProxyCache`

Schedules for deletion the cached manifests and blobs for a group.This endpoint requires the Owner role for the group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | Unauthorized |

