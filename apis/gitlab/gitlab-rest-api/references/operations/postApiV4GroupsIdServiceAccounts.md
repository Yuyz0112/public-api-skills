# POST /api/v4/groups/{id}/service_accounts

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Create a service account user**
**Operation ID:** `postApiV4GroupsIdServiceAccounts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Group not found |

**Success Response Schema:**

[APIEntitiesServiceAccount](../schemas/APIEntitiesServiceAccount/APIEntitiesServiceAccount.md)

