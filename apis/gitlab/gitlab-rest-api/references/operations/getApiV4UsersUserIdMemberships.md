# GET /api/v4/users/{user_id}/memberships

**Resource:** [Users](../resources/Users.md)
**Get memberships**
**Operation ID:** `getApiV4UsersUserIdMemberships`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | integer | Yes | The ID of the user |
| `type` | query | enum: Project, Namespace | No | Filter memberships by type |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMembership](../schemas/APIEntitiesMembership/APIEntitiesMembership.md)

