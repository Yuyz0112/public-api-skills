# POST /accounts/{account_id}/magic/sites/{site_id}/wans

**Resource:** [Magic Site WANs](../resources/Magic-Site-WANs.md)
**Create a new Site WAN**
**Operation ID:** `magic-site-wans-create-wan`

Creates a new Site WAN.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_wans_add_single_request](../schemas/magic/magic-wans-add-single-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Site WAN response |
| 4XX | Create Site WAN response failure |

**Success Response Schema:**

[magic_wans_collection_response](../schemas/magic/magic-wans-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
