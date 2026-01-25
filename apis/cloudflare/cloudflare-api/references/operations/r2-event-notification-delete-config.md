# DELETE /accounts/{account_id}/event_notifications/r2/{bucket_name}/configuration/queues/{queue_id}

**Resource:** [R2 Bucket](../resources/R2-Bucket.md)
**Delete Event Notification Rules**
**Operation ID:** `r2-event-notification-delete-config`

Delete an event notification rule. **If no body is provided, all rules for specified queue will be deleted**.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `queue_id` | path | r2_queue_identifier | Yes |  |
| `bucket_name` | path | r2_bucket_name | Yes |  |
| `account_id` | path | r2_account_identifier | Yes |  |
| `cf-r2-jurisdiction` | header | r2_jurisdiction | No |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Configuration response. |
| 4XX | Delete Configuration failure. |

## Security

- **api_token**
