# GET /accounts/{account_id}/magic/routes

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**List Routes**
**Operation ID:** `magic-static-routes-list-routes`

List all Magic static routes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Routes response |
| 4XX | List Routes response failure |

**Success Response Schema:**

[magic_routes_collection_response](../schemas/magic/magic-routes-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
