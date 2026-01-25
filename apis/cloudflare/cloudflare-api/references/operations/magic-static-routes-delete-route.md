# DELETE /accounts/{account_id}/magic/routes/{route_id}

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**Delete Route**
**Operation ID:** `magic-static-routes-delete-route`

Disable and remove a specific Magic static route.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | magic_identifier | Yes |  |
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Route response |
| 4XX | Delete Route response failure |

**Success Response Schema:**

[magic_route_deleted_response](../schemas/magic/magic-route-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
