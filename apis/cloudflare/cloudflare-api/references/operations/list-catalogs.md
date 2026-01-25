# GET /accounts/{account_id}/r2-catalog

**Resource:** [R2 Catalog Management](../resources/R2-Catalog-Management.md)
**List R2 catalogs**
**Operation ID:** `list-catalogs`

Returns a list of R2 buckets that have been enabled as Apache Iceberg catalogs
for the specified account. Each catalog represents an R2 bucket configured
to store Iceberg metadata and data files.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of R2 catalogs. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
