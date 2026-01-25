# PUT /accounts/{account_id}/magic/apps/{account_app_id}

**Resource:** [Magic Account Apps](../resources/Magic-Account-Apps.md)
**Update an App**
**Operation ID:** `magic-account-apps-update-app`

Updates an Account App

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `account_app_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_app_update_request](../schemas/magic/magic-app-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update App response |
| 4XX | Update App response failure |

**Success Response Schema:**

[magic_app_single_response](../schemas/magic/magic-app-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
