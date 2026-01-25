# PUT /accounts/{account_id}/calls/apps/{app_id}

**Resource:** [Calls Apps](../resources/Calls-Apps.md)
**Edit app details**
**Operation ID:** `calls-apps-update-app-details`

Edit details for a single app.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | calls_identifier | Yes |  |
| `account_id` | path | calls_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [calls_app_editable_fields](../schemas/calls/calls-app-editable-fields.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit app details response |
| 4XX | Edit app details response failure |

**Success Response Schema:**

[calls_app_response_single](../schemas/calls/calls-app-response-single.md)

## Security

- **api_token**
