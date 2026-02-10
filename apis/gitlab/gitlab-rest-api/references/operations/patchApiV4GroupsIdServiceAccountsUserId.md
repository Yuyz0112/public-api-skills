# PATCH /api/v4/groups/{id}/service_accounts/{user_id}

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Update a service account user**
**Operation ID:** `patchApiV4GroupsIdServiceAccountsUserId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `user_id` | path | integer | Yes | The ID of the service account user |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 User not found |

**Success Response Schema:**

[APIEntitiesServiceAccount](../schemas/APIEntitiesServiceAccount/APIEntitiesServiceAccount.md)

