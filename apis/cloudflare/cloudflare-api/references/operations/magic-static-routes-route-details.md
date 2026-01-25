# GET /accounts/{account_id}/magic/routes/{route_id}

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**Route Details**
**Operation ID:** `magic-static-routes-route-details`

Get a specific Magic static route.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Route Details response |
| 4XX | Route Details response failure |

**Success Response Schema:**

[magic_route_single_response](../schemas/magic/magic-route-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
