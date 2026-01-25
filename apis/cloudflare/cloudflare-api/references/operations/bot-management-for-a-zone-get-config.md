# GET /zones/{zone_id}/bot_management

**Resource:** [Bot Settings](../resources/Bot-Settings.md)
**Get Zone Bot Management Config**
**Operation ID:** `bot-management-for-a-zone-get-config`

Retrieve a zone's Bot Management Config

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bot-management_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Bot Management config response |
| 4XX | Bot Management config response failure |

**Success Response Schema:**

[bot-management_bot_management_response_body](../schemas/bot-management/bot-management-bot-management-response-body.md)

## Security

- **api_token**
- **api_email**
- **api_key**
