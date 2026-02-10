# PATCH /api/v4/groups/{id}/enterprise_users/{user_id}

**Resource:** [Group enterprise users](../resources/Group-enterprise-users.md)
**Modify an enterprise user**
**Operation ID:** `patchApiV4GroupsIdEnterpriseUsersUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `user_id` | path | integer | Yes | ID of user account. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserPublic](../schemas/APIEntitiesUserPublic/APIEntitiesUserPublic.md)

