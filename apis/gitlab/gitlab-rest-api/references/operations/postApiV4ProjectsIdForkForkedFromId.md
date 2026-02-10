# POST /api/v4/projects/{id}/fork/{forked_from_id}

**Resource:** [Projects](../resources/Projects.md)
**Mark this project as forked from another**
**Operation ID:** `postApiV4ProjectsIdForkForkedFromId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `forked_from_id` | path | string | Yes | The ID of the project it was forked from |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProject](../schemas/APIEntitiesProject/APIEntitiesProject.md)

