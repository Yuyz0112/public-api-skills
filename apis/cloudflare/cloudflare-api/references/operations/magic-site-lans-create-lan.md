# POST /accounts/{account_id}/magic/sites/{site_id}/lans

**Resource:** [Magic Site LANs](../resources/Magic-Site-LANs.md)
**Create a new Site LAN**
**Operation ID:** `magic-site-lans-create-lan`

Creates a new Site LAN. If the site is in high availability mode, static_addressing is required along with secondary and virtual address.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_lans_add_single_request](../schemas/magic/magic-lans-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Site LAN response |
| 4XX | Create Site LAN response failure |

**Success Response Schema:**

[magic_lans_collection_response](../schemas/magic/magic-lans-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
