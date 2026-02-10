# POST /api/v4/projects/{id}/runners

**Resource:** [Runners](../resources/Runners.md)
**Assign a runner to project**
**Operation ID:** `postApiV4ProjectsIdRunners`

Assign an available project runner to the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 403 | Runner is locked |
| 404 | Runner not found |

**Success Response Schema:**

[APIEntitiesCiRunner](../schemas/APIEntitiesCiRunner/APIEntitiesCiRunner.md)

