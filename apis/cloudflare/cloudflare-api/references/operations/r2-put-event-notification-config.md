# PUT /accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration/queues/{queue_id}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Create Event Notification Rule**
**Operation ID:** `r2-put-event-notification-config`

Create event notification rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | r2_queue_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Configuration response. |
| 4XX | Create Configuration failure. |

## Security

- **api_token**
