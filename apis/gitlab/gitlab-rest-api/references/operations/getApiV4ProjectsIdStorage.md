# GET /api/v4/projects/{id}/storage

**Resource:** [Projects](../resources/Projects.md)
**Show the storage information**
**Operation ID:** `getApiV4ProjectsIdStorage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID of a project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |

**Success Response Schema:**

[APIEntitiesProjectRepositoryStorage](../schemas/APIEntitiesProjectRepositoryStorage/APIEntitiesProjectRepositoryStorage.md)

