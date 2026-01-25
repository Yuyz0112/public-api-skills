# GET /accounts/{account_id}/calls/apps/{app_id}

**Resource:** [Calls Apps](../resources/Calls-Apps.md)
**Retrieve app details**
**Operation ID:** `calls-apps-retrieve-app-details`

Fetches details for a single Calls app.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | calls_identifier | Yes |  |
| `account_id` | path | calls_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve app details response |
| 4XX | Retrieve app details response failure |

**Success Response Schema:**

[calls_app_response_single](../schemas/calls/calls-app-response-single.md)

## Security

- **api_token**
