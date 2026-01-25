# PUT /accounts/{account_id}/magic/sites/{site_id}

**Resource:** [Magic Sites](../resources/Magic-Sites.md)
**Update Site**
**Operation ID:** `magic-sites-update-site`

Update a specific Site.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `site_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_site_update_request](../schemas/magic/magic-site-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Site response |
| 4XX | Update Site response failure |

**Success Response Schema:**

[magic_site_modified_response](../schemas/magic/magic-site-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
