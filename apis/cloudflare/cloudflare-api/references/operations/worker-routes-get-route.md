# GET /zones/{zone_id}/workers/routes/{route_id}

**Resource:** [Worker Routes](../resources/Worker-Routes.md)
**Get Route**
**Operation ID:** `worker-routes-get-route`

Returns information about a route, including URL pattern and Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | workers_identifier | Yes |  |
| `zone_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Route response. |
| 4XX | Get Route response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
