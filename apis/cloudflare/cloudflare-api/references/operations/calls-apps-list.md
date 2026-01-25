# GET /accounts/{account_id}/calls/apps

**Resource:** [Calls Apps](../resources/Calls-Apps.md)
**List apps**
**Operation ID:** `calls-apps-list`

Lists all apps in the Cloudflare account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | calls_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List apps response |
| 4XX | List apps response failure |

**Success Response Schema:**

[calls_app_response_collection](../schemas/calls/calls-app-response-collection.md)

## Security

- **api_token**
