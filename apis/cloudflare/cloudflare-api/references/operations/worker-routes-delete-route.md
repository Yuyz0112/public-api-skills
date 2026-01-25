# DELETE /zones/{zone_id}/workers/routes/{route_id}

**Resource:** [Worker Routes](../resources/Worker-Routes.md)
**Delete Route**
**Operation ID:** `worker-routes-delete-route`

Deletes a route.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | workers_identifier | Yes |  |
| `zone_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Route response. |
| 4XX | Delete Route response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
