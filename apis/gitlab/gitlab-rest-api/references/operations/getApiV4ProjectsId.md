# GET /api/v4/projects/{id}

**Resource:** [Projects](../resources/Projects.md)
**Get a single project**
**Operation ID:** `getApiV4ProjectsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `statistics` | query | boolean | No | Include project statistics |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |
| `license` | query | boolean | No | Include project license data |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectWithAccess](../schemas/APIEntitiesProjectWithAccess/APIEntitiesProjectWithAccess.md)

