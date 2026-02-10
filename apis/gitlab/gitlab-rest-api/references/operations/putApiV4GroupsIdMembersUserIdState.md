# PUT /api/v4/groups/{id}/members/{user_id}/state

**Resource:** [Members](../resources/Members.md)
**Changes the state of the memberships of a user in the group**
**Operation ID:** `putApiV4GroupsIdMembersUserIdState`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `user_id` | path | integer | Yes | The user ID of the user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

