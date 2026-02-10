# GET /api/v4/runners/{id}/projects

**Resource:** [Runners](../resources/Runners.md)
**Get projects associated with a runner**
**Operation ID:** `getApiV4RunnersIdProjects`

Get a paginated list of all projects associated with the specified runner. Access is restricted based on user permissions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a runner |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | No access granted |
| 404 | Runner not found |

**Success Response Schema:**

[APIEntitiesBasicProjectDetails](../schemas/APIEntitiesBasicProjectDetails/APIEntitiesBasicProjectDetails.md)

