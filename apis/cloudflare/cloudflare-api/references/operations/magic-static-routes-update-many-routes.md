# PUT /accounts/{account_id}/magic/routes

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**Update Many Routes**
**Operation ID:** `magic-static-routes-update-many-routes`

Update multiple Magic static routes. Use `?validate_only=true` as an optional query parameter to run validation only without persisting changes. Only fields for a route that need to be changed need be provided.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_route_update_many_request](../schemas/magic/magic-route-update-many-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Many Routes response |
| 4XX | Update Many Routes response failure |

**Success Response Schema:**

[magic_multiple_route_modified_response](../schemas/magic/magic-multiple-route-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
