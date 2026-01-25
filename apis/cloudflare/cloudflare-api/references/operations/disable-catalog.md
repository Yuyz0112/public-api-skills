# POST /accounts/{account_id}/r2-catalog/{bucket_name}/disable

**Resource:** [R2 Catalog Management](../resources/R2-Catalog-Management.md)
**Disable R2 catalog**
**Operation ID:** `disable-catalog`

Disable an R2 bucket as a catalog. This operation deactivates the catalog
but preserves existing metadata and data files. The catalog can be
re-enabled later.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name to disable as catalog. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Catalog disabled successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
