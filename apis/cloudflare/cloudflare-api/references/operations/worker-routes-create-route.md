# POST /zones/{zone_id}/workers/routes

**Resource:** [Worker Routes](../resources/Worker-Routes.md)
**Create Route**
**Operation ID:** `worker-routes-create-route`

Creates a route that maps a URL pattern to a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | workers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_route](../schemas/workers/workers-route.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Route response. |
| 4XX | Create Route response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
