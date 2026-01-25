# POST /accounts/{account_id}/magic/sites

**Resource:** [Magic Sites](../resources/Magic-Sites.md)
**Create a new Site**
**Operation ID:** `magic-sites-create-site`

Creates a new Site

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_sites_add_single_request](../schemas/magic/magic-sites-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Site response |
| 4XX | Create Site response failure |

**Success Response Schema:**

[magic_site_single_response](../schemas/magic/magic-site-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
