# GET /accounts/{account_id}/r2/buckets/{bucket_name}/lifecycle

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Get Object Lifecycle Rules**
**Operation ID:** `r2-get-bucket-lifecycle-configuration`

Get object lifecycle rules for a bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success Response. |
| 4XX | Error Response. |

## Security

- **api_token**
