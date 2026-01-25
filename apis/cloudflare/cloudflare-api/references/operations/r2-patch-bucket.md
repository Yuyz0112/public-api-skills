# PATCH /accounts/{account_id}/r2/buckets/{bucket_name}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Patch Bucket**
**Operation ID:** `r2-patch-bucket`

Updates properties of an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |
| `cf-r2-storage-class` | header | any | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Patch Bucket response. |
| 4XX | Get Bucket response failure. |

## Security

- **api_token**
