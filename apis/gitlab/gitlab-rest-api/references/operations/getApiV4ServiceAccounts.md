# GET /api/v4/service_accounts

**Resource:** [Service accounts](../resources/Service-accounts.md)
**Get list of service account users. Available only for instance admins**
**Operation ID:** `getApiV4ServiceAccounts`

Get list of service account users

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

**Success Response Schema:**

[APIEntitiesServiceAccount](../schemas/APIEntitiesServiceAccount/APIEntitiesServiceAccount.md)

