# DELETE /api/v4/groups/{id}/enterprise_users/{user_id}

**Resource:** [Group enterprise users](../resources/Group-enterprise-users.md)
**Delete an enterprise user**
**Operation ID:** `deleteApiV4GroupsIdEnterpriseUsersUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `user_id` | path | integer | Yes | ID of user account. |
| `hard_delete` | query | boolean | No | If `false`, deletes the user and moves their contributions to a system-wide "Ghost User". If `true`, deletes the user, their associated contributions, and any groups owned solely by the user. Default value: `false`. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

