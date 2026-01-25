# POST /accounts/{account_id}/r2/buckets

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Create Bucket**
**Operation ID:** `r2-create-bucket`

Creates a new R2 bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Bucket response. |
| 4XX | Create Bucket response failure. |

## Security

- **api_token**
