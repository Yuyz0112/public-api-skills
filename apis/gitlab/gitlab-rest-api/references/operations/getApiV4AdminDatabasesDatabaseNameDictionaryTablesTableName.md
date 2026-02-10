# GET /api/v4/admin/databases/{database_name}/dictionary/tables/{table_name}

**Resource:** [Database dictionary](../resources/Database-dictionary.md)
**Retrieve dictionary details**
**Operation ID:** `getApiV4AdminDatabasesDatabaseNameDictionaryTablesTableName`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `database_name` | path | enum: main, ci | Yes | The database name |
| `table_name` | path | string | Yes | The table name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesDictionaryTable](../schemas/APIEntitiesDictionaryTable/APIEntitiesDictionaryTable.md)

