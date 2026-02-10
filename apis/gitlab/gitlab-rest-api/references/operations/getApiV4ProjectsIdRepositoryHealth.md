# GET /api/v4/projects/{id}/repository/health

**Resource:** [Repositories](../resources/Repositories.md)
**Get repository health**
**Operation ID:** `getApiV4ProjectsIdRepositoryHealth`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `generate` | query | boolean | No | Triggers a new health report to be generated |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesRepositoryHealth](../schemas/APIEntitiesRepositoryHealth/APIEntitiesRepositoryHealth.md)

