# PATCH /api/v4/service_accounts/{user_id}

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Update a service account user. Available only for instance admins.**
**Operation ID:** `patchApiV4ServiceAccountsUserId`

Update a service account user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesServiceAccount](../schemas/APIEntitiesServiceAccount/APIEntitiesServiceAccount.md)

