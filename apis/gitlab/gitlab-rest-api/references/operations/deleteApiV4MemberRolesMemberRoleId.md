# DELETE /api/v4/member_roles/{member_role_id}

**Resource:** [Member roles](../resources/Member-roles.md)
**Delete Member Role**
**Operation ID:** `deleteApiV4MemberRolesMemberRoleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `member_role_id` | path | integer | Yes | ID of the member role |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | 404 Member Role Not Found |

