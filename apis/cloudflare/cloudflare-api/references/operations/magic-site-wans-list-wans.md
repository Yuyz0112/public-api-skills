# GET /accounts/{account_id}/magic/sites/{site_id}/wans

**Resource:** [Magic Site WANs](../resources/Magic-Site-WANs.md)
**List Site WANs**
**Operation ID:** `magic-site-wans-list-wans`

Lists Site WANs associated with an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `site_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Site WANs response |
| 4XX | List Site WANs response failure |

**Success Response Schema:**

[magic_wans_collection_response](../schemas/magic/magic-wans-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
