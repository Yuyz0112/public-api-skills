# GET /accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**List Event Notification Rules**
**Operation ID:** `r2-get-event-notification-configs`

List all event notification rules for a bucket.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Read Configuration response. |
| 404 | No Configuration Found response. |
| 4XX | Read Configuration failure. |

## Security

- **api_token**
