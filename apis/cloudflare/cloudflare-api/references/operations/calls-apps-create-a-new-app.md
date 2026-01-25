# POST /accounts/{account_id}/calls/apps

**Resource:** [Calls Apps](../resources/Calls-Apps.md)
**Create a new app**
**Operation ID:** `calls-apps-create-a-new-app`

Creates a new Cloudflare calls app. An app is an unique enviroment where each Session can access all Tracks within the app.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | calls_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [calls_app_editable_fields](../schemas/calls/calls-app-editable-fields.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created a new app |

**Success Response Schema:**

[calls_app_response_single_with_secret](../schemas/calls/calls-app-response-single-with-secret.md)

## Security

- **api_token**
