# POST /api/v4/projects/{id}/fork

**Resource:** [Projects](../resources/Projects.md)
**Fork new project for the current user or provided namespace.**
**Operation ID:** `postApiV4ProjectsIdFork`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 403 | Unauthenticated |
| 404 | Not found |
| 409 | Conflict |

**Success Response Schema:**

[APIEntitiesProject](../schemas/APIEntitiesProject/APIEntitiesProject.md)

