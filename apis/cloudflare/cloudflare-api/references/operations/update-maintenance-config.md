# POST /accounts/{account_id}/r2-catalog/{bucket_name}/maintenance-configs

**Resource:** [Maintenance Configuration](../resources/Maintenance-Configuration.md)
**Update catalog maintenance configuration**
**Operation ID:** `update-maintenance-config`

Update the maintenance configuration for a catalog. This allows you to
enable or disable compaction and adjust target file sizes for optimization.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2-data-catalog_catalog-maintenance-update-request](../schemas/r2-data-catalog/r2-data-catalog-catalog-maintenance-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Maintenance configuration updated successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
