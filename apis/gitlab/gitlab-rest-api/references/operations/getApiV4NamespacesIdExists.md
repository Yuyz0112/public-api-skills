# GET /api/v4/namespaces/{id}/exists

**Resource:** [Namespaces](../resources/Namespaces.md)
**Get existence of a namespace**
**Operation ID:** `getApiV4NamespacesIdExists`

Get existence of a namespace by path. Suggests a new namespace path that does not already exist.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | Namespace’s path |
| `parent_id` | query | integer | No | The ID of the parent namespace. If no ID is specified, only top-level namespaces are considered. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesNamespaceExistence](../schemas/APIEntitiesNamespaceExistence/APIEntitiesNamespaceExistence.md)

