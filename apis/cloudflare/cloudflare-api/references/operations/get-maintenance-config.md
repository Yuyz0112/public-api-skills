# GET /accounts/{account_id}/r2-catalog/{bucket_name}/maintenance-configs

**Resource:** [Maintenance Configuration](../resources/Maintenance-Configuration.md)
**Get catalog maintenance configuration**
**Operation ID:** `get-maintenance-config`

Retrieve the maintenance configuration for a specific catalog,
including compaction settings and credential status.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Maintenance configuration retrieved successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
