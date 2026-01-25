# GET /accounts/{account_id}/r2/metrics

**Resource:** [R2 Account](../resources/R2-Account.md)
**Get Account-Level Metrics**
**Operation ID:** `r2-get-account-level-metrics`

Get Storage/Object Count Metrics across all buckets in your account. Note that Account-Level Metrics may not immediately reflect the latest data.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | r2_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Account-Level Metrics response. |
| 4XX | Get Account-Level Metrics response failure. |

## Security

- **api_token**
