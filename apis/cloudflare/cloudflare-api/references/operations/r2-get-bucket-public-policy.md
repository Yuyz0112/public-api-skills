# GET /accounts/{account_id}/r2/buckets/{bucket_name}/domains/managed

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Get r2.dev Domain of Bucket**
**Operation ID:** `r2-get-bucket-public-policy`

Gets state of public access over the bucket's R2-managed (r2.dev) domain.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Managed Subdomain response. |
| 4XX | Get Managed Subdomain response failure. |

## Security

- **api_token**
