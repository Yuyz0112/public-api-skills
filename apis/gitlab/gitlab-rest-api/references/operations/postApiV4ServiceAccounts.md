# POST /api/v4/service_accounts

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Create a service account user. Available only for instance admins.**
**Operation ID:** `postApiV4ServiceAccounts`

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |

**Success Response Schema:**

[APIEntitiesServiceAccount](../schemas/APIEntitiesServiceAccount/APIEntitiesServiceAccount.md)

