# GET /api/v4/namespaces/{id}

**Resource:** [Namespaces](../resources/Namespaces.md)
**Get namespace by ID**
**Operation ID:** `getApiV4NamespacesId`

Get a namespace by ID

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the namespace |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesNamespace](../schemas/APIEntitiesNamespace/APIEntitiesNamespace.md)

