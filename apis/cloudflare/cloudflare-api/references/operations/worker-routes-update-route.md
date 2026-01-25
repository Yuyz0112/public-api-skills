# PUT /zones/{zone_id}/workers/routes/{route_id}

**Resource:** [Worker Routes](../resources/Worker-Routes.md)
**Update Route**
**Operation ID:** `worker-routes-update-route`

Updates the URL pattern or Worker associated with a route.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | workers_identifier | Yes |  |
| `zone_id` | path | workers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_route](../schemas/workers/workers-route.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Route response. |
| 4XX | Update Route response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
