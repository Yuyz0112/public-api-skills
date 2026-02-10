# GET /api/v4/namespaces/storage/limit_exclusions

**Resource:** [Namespaces](../resources/Namespaces.md)
**Retrieve all limit exclusions**
**Operation ID:** `getApiV4NamespacesStorageLimitExclusions`

Gets all records for namespaces that have been excluded

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesNamespacesStorageLimitExclusion](../schemas/APIEntitiesNamespacesStorageLimitExclusion/APIEntitiesNamespacesStorageLimitExclusion.md)

