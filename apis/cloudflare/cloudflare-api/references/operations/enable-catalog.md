# POST /accounts/{account_id}/r2-catalog/{bucket_name}/enable

**Resource:** [R2 Catalog Management](../resources/R2-Catalog-Management.md)
**Enable R2 bucket as a catalog**
**Operation ID:** `enable-catalog`

Enable an R2 bucket as an Apache Iceberg catalog. This operation creates
the necessary catalog infrastructure and activates the bucket for storing
Iceberg metadata and data files.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name to enable as catalog. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Catalog enabled successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 409 | Catalog already enabled. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
