# GET /accounts/{account_id}/r2-catalog/{bucket_name}/namespaces/{namespace}/tables/{table_name}/maintenance-configs

**Resource:** [Table Maintenance Configuration](../resources/Table-Maintenance-Configuration.md)
**Get table maintenance configuration**
**Operation ID:** `get-table-maintenance-config`

Retrieve the maintenance configuration for a specific table,
including compaction settings.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |
| `namespace` | path | string | Yes | The namespace identifier (use %1F as separator for nested namespaces). |
| `table_name` | path | string | Yes | The table name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Table maintenance configuration retrieved successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Table not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
