# DELETE /api/v4/groups/{id}/billable_members/{user_id}

**Resource:** [Members](../resources/Members.md)
**Removes a billable member from a group or project.**
**Operation ID:** `deleteApiV4GroupsIdBillableMembersUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `user_id` | path | integer | Yes | The user ID of the member |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

