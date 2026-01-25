# PUT /accounts/{account_id}/r2/buckets/{bucket_name}/sippy

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Enable Sippy**
**Operation ID:** `r2-put-bucket-sippy-config`

Sets configuration for Sippy for an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set Sippy Configuration response. |
| 4XX | Get Sippy Configuration response failure. |

## Security

- **api_token**
