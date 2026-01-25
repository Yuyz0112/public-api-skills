# DELETE /accounts/{account_id}/r2/buckets/{bucket_name}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Delete Bucket**
**Operation ID:** `r2-delete-bucket`

Deletes an existing R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Bucket response. |
| 4XX | Delete Bucket response failure. |

**Success Response Schema:**

[r2_v4_response](../schemas/r2/r2-v4-response.md)

## Security

- **api_token**
