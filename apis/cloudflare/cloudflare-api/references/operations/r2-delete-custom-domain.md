# DELETE /accounts/{account_id}/r2/buckets/{bucket_name}/domains/custom/{domain}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Remove Custom Domain From Bucket**
**Operation ID:** `r2-delete-custom-domain`

Remove custom domain registration from an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `domain` | path | r2_domain_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Custom Domain response. |
| 4XX | Delete Custom Domain response failure. |

## Security

- **api_token**
