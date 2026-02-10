# GET /api/v4/groups/{id}/service_accounts

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Get list of service account users**
**Operation ID:** `getApiV4GroupsIdServiceAccounts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `order_by` | query | enum: id, username | No | Attribute to sort by |
| `sort` | query | enum: asc, desc | No | Order of sorting |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Group not found |

**Success Response Schema:**

[APIEntitiesServiceAccount](../schemas/APIEntitiesServiceAccount/APIEntitiesServiceAccount.md)

