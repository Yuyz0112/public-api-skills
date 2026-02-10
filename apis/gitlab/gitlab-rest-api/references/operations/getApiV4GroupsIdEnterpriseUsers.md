# GET /api/v4/groups/{id}/enterprise_users

**Resource:** [Group enterprise users](../resources/Group-enterprise-users.md)
**Get a list of enterprise users of the group**
**Operation ID:** `getApiV4GroupsIdEnterpriseUsers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `username` | query | string | No | Return single user with a specific username. |
| `search` | query | string | No | Search users by name, email, username. |
| `active` | query | boolean | No | Return only active users. |
| `blocked` | query | boolean | No | Return only blocked users. |
| `created_after` | query | string (date-time) | No | Return users created after the specified time. |
| `created_before` | query | string (date-time) | No | Return users created before the specified time. |
| `two_factor` | query | string | No | Filter users by two-factor authentication (2FA). Filter values are `enabled` or `disabled`. By default it returns all users. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserPublic](../schemas/APIEntitiesUserPublic/APIEntitiesUserPublic.md)

