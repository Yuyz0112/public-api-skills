# POST /api/v4/namespaces/{id}/storage/limit_exclusion

**Resource:** [Namespaces](../resources/Namespaces.md)
**Creates a storage limit exclusion for a Namespace**
**Operation ID:** `postApiV4NamespacesIdStorageLimitExclusion`

Creates a Namespaces::Storage::LimitExclusion

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesNamespacesStorageLimitExclusion](../schemas/APIEntitiesNamespacesStorageLimitExclusion/APIEntitiesNamespacesStorageLimitExclusion.md)

