# DELETE /accounts/{account_id}/r2/buckets/{bucket_name}/sippy

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Disable Sippy**
**Operation ID:** `r2-delete-bucket-sippy-config`

Disables Sippy on this bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Sippy Configuration response. |
| 4XX | Delete Sippy Configuration response failure. |

## Security

- **api_token**
