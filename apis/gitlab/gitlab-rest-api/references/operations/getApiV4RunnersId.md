# GET /api/v4/runners/{id}

**Resource:** [Runners](../resources/Runners.md)
**Get runner's details**
**Operation ID:** `getApiV4RunnersId`

At least the Maintainer role is required to get runner details at the project and group level. Instance-level runner details via this endpoint are available to all signed in users.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a runner |
| `include_projects` | query | boolean | No | Include projects in the response. Set to false to improve performance for runners with many projects. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | No access granted |
| 404 | Runner not found |

**Success Response Schema:**

[APIEntitiesCiRunnerDetails](../schemas/APIEntitiesCiRunnerDetails/APIEntitiesCiRunnerDetails.md)

