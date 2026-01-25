# PUT /accounts/{account_id}/magic/routes/{route_id}

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**Update Route**
**Operation ID:** `magic-static-routes-update-route`

Update a specific Magic static route. Use `?validate_only=true` as an optional query parameter to run validation only without persisting changes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_route_update_request](../schemas/magic/magic-route-update-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Route response |
| 4XX | Update Route response failure |

**Success Response Schema:**

[magic_route_modified_response](../schemas/magic/magic-route-modified-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
