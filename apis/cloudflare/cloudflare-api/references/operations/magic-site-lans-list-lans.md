# GET /accounts/{account_id}/magic/sites/{site_id}/lans

**Resource:** [Magic Site LANs](../resources/Magic-Site-LANs.md)
**List Site LANs**
**Operation ID:** `magic-site-lans-list-lans`

Lists Site LANs associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Site LANs response |
| 4XX | List Site LANs response failure |

**Success Response Schema:**

[magic_lans_collection_response](../schemas/magic/magic-lans-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
