# GET /zones/{zone_id}/bot_management/feedback

**Resource:** [Feedback](../resources/Feedback.md)
**List zone feedback reports**
**Operation ID:** `bot-management-zone-feedback-list`

Returns all feedback reports previously submitted for the specified zone. Feedback reports help improve detection by sharing samples of traffic that were misclassified as bots or humans.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bot-management_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of feedback reports |
| 4XX | Feedback list failure |

**Success Response Schema:**

Array of [bot-management_feedback_report](../schemas/bot-management/bot-management-feedback-report.md)

## Security

- **api_token**
- **api_email**
- **api_key**
