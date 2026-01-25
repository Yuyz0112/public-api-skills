# POST /accounts/{account_id}/r2-catalog/{bucket_name}/namespaces/{namespace}/tables/{table_name}/maintenance-configs

**Resource:** [Table Maintenance Configuration](../resources/Table-Maintenance-Configuration.md)
**Update table maintenance configuration**
**Operation ID:** `update-table-maintenance-config`

Update the maintenance configuration for a specific table. This allows you to
enable or disable compaction and adjust target file sizes for optimization.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |
| `namespace` | path | string | Yes | The namespace identifier (use %1F as separator for nested namespaces). |
| `table_name` | path | string | Yes | The table name. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2-data-catalog_table-maintenance-update-request](../schemas/r2-data-catalog/r2-data-catalog-table-maintenance-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Table maintenance configuration updated successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Table not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
