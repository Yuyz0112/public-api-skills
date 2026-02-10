# GET /api/v4/users/{id}

**Resource:** [Users](../resources/Users.md)
**Get a single user**
**Operation ID:** `getApiV4UsersId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUser](../schemas/APIEntitiesUser/APIEntitiesUser.md)

