# GET /api/v4/groups/{id}/provisioned_users

**Resource:** [Groups](../resources/Groups.md)
**Get a list of users provisioned by the group**
**Operation ID:** `getApiV4GroupsIdProvisionedUsers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | Return a single user with a specific username |
| `search` | query | string | No | Search users by name, email or username |
| `active` | query | boolean | No | Return only active users |
| `blocked` | query | boolean | No | Return only blocked users |
| `created_after` | query | string (date-time) | No | Return users created after the specified time |
| `created_before` | query | string (date-time) | No | Return users created before the specified time |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserPublic](../schemas/APIEntitiesUserPublic/APIEntitiesUserPublic.md)

