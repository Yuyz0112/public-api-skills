# DELETE /api/v4/groups/{id}/members/{user_id}

**Resource:** [Members](../resources/Members.md)
**Removes a user from a group or project.**
**Operation ID:** `deleteApiV4GroupsIdMembersUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The group ID |
| `user_id` | path | integer | Yes | The user ID of the member |
| `skip_subresources` | query | boolean | No | Flag indicating if the deletion of direct memberships of the removed member in subgroups and projects should be skipped |
| `unassign_issuables` | query | boolean | No | Flag indicating if the removed member should be unassigned from any issues or merge requests within given group or project |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

