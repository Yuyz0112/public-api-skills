# PUT /api/v4/groups/{id}

**Resource:** [Groups](../resources/Groups.md)
**Update a group. Available only for users who can administrate groups.**
**Operation ID:** `putApiV4GroupsId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroup](../schemas/APIEntitiesGroup/APIEntitiesGroup.md)

