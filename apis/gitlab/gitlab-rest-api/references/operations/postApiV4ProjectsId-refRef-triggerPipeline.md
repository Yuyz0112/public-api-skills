# POST /api/v4/projects/{id}/(ref/{ref}/)trigger/pipeline

**Resource:** [CI triggers](../resources/CI-triggers.md)
**Trigger a GitLab project pipeline**
**Operation ID:** `postApiV4ProjectsId(refRef)triggerPipeline`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `ref` | path | string | Yes | The commit sha or name of a branch or tag |

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

[APIEntitiesCiPipeline](../schemas/APIEntitiesCiPipeline/APIEntitiesCiPipeline.md)

