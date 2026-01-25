# DELETE /accounts/{account_id}/magic/routes

**Resource:** [Magic Static Routes](../resources/Magic-Static-Routes.md)
**Delete Many Routes**
**Operation ID:** `magic-static-routes-delete-many-routes`

Delete multiple Magic static routes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [magic_route_delete_many_request](../schemas/magic/magic-route-delete-many-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Many Routes response |
| 4XX | Delete Many Routes response failure |

**Success Response Schema:**

[magic_multiple_route_delete_response](../schemas/magic/magic-multiple-route-delete-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
