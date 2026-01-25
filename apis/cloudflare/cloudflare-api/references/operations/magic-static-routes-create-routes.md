# POST /accounts/{account_id}/magic/routes

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**Create a Route**
**Operation ID:** `magic-static-routes-create-routes`

Creates a new Magic static route. Use `?validate_only=true` as an optional query parameter to run validation only without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_create_route_request](../schemas/magic/magic-create-route-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Routes response |
| 4XX | Create Routes response failure |

**Success Response Schema:**

[magic_create_route_response](../schemas/magic/magic-create-route-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
