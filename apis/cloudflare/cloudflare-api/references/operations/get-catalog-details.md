# GET /accounts/{account_id}/r2-catalog/{bucket_name}

**Resource:** [R2 Catalog Management](../resources/R2-Catalog-Management.md)
**Get R2 catalog details**
**Operation ID:** `get-catalog-details`

Retrieve detailed information about a specific R2 catalog by bucket name.
Returns catalog status, maintenance configuration, and credential status.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2-data-catalog_account-id | Yes | Identifies the account. |
| `bucket_name` | path | r2-data-catalog_bucket-name | Yes | Specifies the R2 bucket name. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | R2 catalog details. |
| 400 | Bad request. |
| 401 | Authentication failed. |
| 403 | Forbidden. |
| 404 | Catalog not found. |
| 500 | Internal server error. |

## Security

- **api_token**
- **api_email**
- **api_key**
