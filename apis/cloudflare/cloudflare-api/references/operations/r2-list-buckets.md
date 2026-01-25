# GET /accounts/{account_id}/r2/buckets

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**List Buckets**
**Operation ID:** `r2-list-buckets`

Lists all R2 buckets on your account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |
| `name_contains` | query | string | No |  |
| `start_after` | query | string | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: name | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `cursor` | query | string | No |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Buckets response. |
| 4XX | List Buckets response failure. |

## Security

- **api_token**
