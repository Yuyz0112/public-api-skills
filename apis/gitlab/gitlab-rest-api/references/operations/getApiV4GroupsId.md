# GET /api/v4/groups/{id}

**Resource:** [Groups](../resources/Groups.md)
**Get a single group, with containing projects.**
**Operation ID:** `getApiV4GroupsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |
| `with_projects` | query | boolean | No | Omit project details |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupDetail](../schemas/APIEntitiesGroupDetail/APIEntitiesGroupDetail.md)

