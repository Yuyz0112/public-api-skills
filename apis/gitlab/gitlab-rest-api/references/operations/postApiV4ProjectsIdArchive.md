# POST /api/v4/projects/{id}/archive

**Resource:** [Projects](../resources/Projects.md)
**Archive a project**
**Operation ID:** `postApiV4ProjectsIdArchive`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 403 | Unauthenticated |

**Success Response Schema:**

[APIEntitiesProject](../schemas/APIEntitiesProject/APIEntitiesProject.md)

