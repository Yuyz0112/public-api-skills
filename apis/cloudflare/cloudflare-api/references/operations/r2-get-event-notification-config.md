# GET /accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration/queues/{queue_id}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Get Event Notification Rule**
**Operation ID:** `r2-get-event-notification-config`

Get a single event notification rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | r2_queue_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | enum: default, eu, fedramp | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Read Configuration response. |
| 404 | No Configuration Found response. |
| 4XX | Read Configuration failure. |

## Security

- **api_token**
