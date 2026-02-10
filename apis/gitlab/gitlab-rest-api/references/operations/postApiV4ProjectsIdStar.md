# POST /api/v4/projects/{id}/star

**Resource:** [Projects](../resources/Projects.md)
**Star a project**
**Operation ID:** `postApiV4ProjectsIdStar`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 304 | Not modified |
| 403 | Unauthenticated |

**Success Response Schema:**

[APIEntitiesProject](../schemas/APIEntitiesProject/APIEntitiesProject.md)

