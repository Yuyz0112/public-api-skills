# GET /api/v4/groups/{id}/billable_members

**Resource:** [Groups](../resources/Groups.md)
**Gets a list of billable users of top-level group.**
**Operation ID:** `getApiV4GroupsIdBillableMembers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `search` | query | string | No | The exact name of the subscribed member |
| `sort` | query | enum: access_level_asc, access_level_desc, last_joined... | No | The sorting option |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)

