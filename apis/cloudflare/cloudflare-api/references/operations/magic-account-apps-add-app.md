# POST /accounts/{account_id}/magic/apps

**Resource:** [Magic Account Apps](../resources/Magic-Account-Apps.md)
**Create a new App**
**Operation ID:** `magic-account-apps-add-app`

Creates a new App for an account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_app_add_single_request](../schemas/magic/magic-app-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create Account App response |
| 4XX | Create Account App response failure |

**Success Response Schema:**

[magic_app_single_response](../schemas/magic/magic-app-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
