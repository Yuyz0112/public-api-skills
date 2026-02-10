# PATCH /api/v4/admin/zoekt/namespaces/{id}

**Resource:** [Code search](../resources/Code-search.md)
**Update the number of replicas override for an enabled namespace**
**Operation ID:** `patchApiV4AdminZoektNamespacesId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the namespace |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad Request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesSearchZoektIndexedNamespace](../schemas/APIEntitiesSearchZoektIndexedNamespace/APIEntitiesSearchZoektIndexedNamespace.md)

