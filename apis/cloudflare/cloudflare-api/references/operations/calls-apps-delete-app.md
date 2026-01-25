# DELETE /accounts/{account_id}/calls/apps/{app_id}

**Resource:** [Calls Apps](../resources/Calls-Apps.md)
**Delete app**
**Operation ID:** `calls-apps-delete-app`

Deletes an app from Cloudflare Calls

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | calls_identifier | Yes |  |
| `account_id` | path | calls_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete app response |
| 4XX | Delete app response failure |

**Success Response Schema:**

[calls_app_response_single](../schemas/calls/calls-app-response-single.md)

## Security

- **api_token**
