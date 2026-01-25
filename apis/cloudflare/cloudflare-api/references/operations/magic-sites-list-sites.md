# GET /accounts/{account_id}/magic/sites

**Resource:** [Magic Sites](../resources/Magic-Sites.md)
**List Sites**
**Operation ID:** `magic-sites-list-sites`

Lists Sites associated with an account. Use connectorid query param to return sites where connectorid matches either site.ConnectorID or site.SecondaryConnectorID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |
| `connectorid` | query | magic_identifier | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Sites response |
| 4XX | List Sites response failure |

**Success Response Schema:**

[magic_sites_collection_response](../schemas/magic/magic-sites-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
