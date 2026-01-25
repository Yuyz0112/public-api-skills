# POST /accounts/{account_id}/r2-catalog/{bucket_name}/credential

**Resource:** [Credential Management](../resources/Credential-Management.md)
**Store catalog credentials**
**Operation ID:** `store-credentials`

Store authentication credentials for a catalog. These credentials are used
to authenticate with R2 storage when performing catalog operations.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [r2-data-catalog_catalog-credential-request](../schemas/r2-data-catalog/r2-data-catalog-catalog-credential-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Credentials stored successfully. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
