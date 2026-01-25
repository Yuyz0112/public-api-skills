# GET /accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom/{domain}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Get Custom Domain Settings**
**Operation ID:** `r2-get-custom-domain-settings`

Get the configuration for a custom domain on an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `domain` | path | r2_domain_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Custom Domain Configuration response. |
| 4XX | Get Custom Domain Configuration response failure. |

## Security

- **api_token**
