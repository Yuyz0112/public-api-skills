# DELETE /api/v4/groups/{id}/members/{user_id}/override

**Resource:** [Members](../resources/Members.md)
**Remove an LDAP group member access level override.**
**Operation ID:** `deleteApiV4GroupsIdMembersUserIdOverride`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `user_id` | path | integer | Yes | The user ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

