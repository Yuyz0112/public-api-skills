# GET /accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**List Custom Domains of Bucket**
**Operation ID:** `r2-list-custom-domains`

Gets a list of all custom domains registered with an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Custom Domains response. |
| 4XX | List Custom Domains response failure. |

## Security

- **api_token**
