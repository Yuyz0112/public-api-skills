# GET /accounts/{account_id}/magic/apps

**Resource:** [Magic Account Apps](../resources/Magic-Account-Apps.md)
**List Apps**
**Operation ID:** `magic-account-apps-list-apps`

Lists Apps associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Apps response |
| 4XX | List Apps response failure |

**Success Response Schema:**

[magic_apps_collection_response](../schemas/magic/magic-apps-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
