# DELETE /accounts/{account_id}/magic/sites/{site_id}

**Resource:** [Magic Sites](../resources/Magic-Sites.md)
**Delete Site**
**Operation ID:** `magic-sites-delete-site`

Remove a specific Site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Site response |
| 4XX | Delete Site response failure |

**Success Response Schema:**

[magic_site_deleted_response](../schemas/magic/magic-site-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
