# GET /api/v4/groups/{id}/billable_members/{user_id}/indirect

**Resource:** [Members](../resources/Members.md)
**Get the indirect memberships of a billable user of a top-level group.**
**Operation ID:** `getApiV4GroupsIdBillableMembersUserIdIndirect`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `user_id` | path | integer | Yes | The user ID of the member |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesBillableMembership](../schemas/APIEntitiesBillableMembership/APIEntitiesBillableMembership.md)

