# POST /zones/{zone_id}/bot_management/feedback

**Resource:** [Feedback](../resources/Feedback.md)
**Submit a feedback report**
**Operation ID:** `bot-management-zone-feedback-create`

Submit a feedback report for the specified zone. Use `type` to indicate whether the report is a false positive (good traffic flagged as bot) or a false negative (bot traffic missed). Furthermore, you can also use `expression` as a wirefilter to identify the affected traffic sample.

See more accepted API fields and expression types at https://developers.cloudflare.com/bots/concepts/feedback-loop/#api-fields and https://developers.cloudflare.com/bots/concepts/feedback-loop/#expression-fields, respectively.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bot-management_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [bot-management_feedback_report](../schemas/bot-management/bot-management-feedback-report.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Feedback report created |
| 4XX | Feedback creation failure |

## Security

- **api_token**
- **api_email**
- **api_key**
