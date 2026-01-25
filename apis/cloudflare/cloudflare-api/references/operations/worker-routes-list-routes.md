# GET /zones/{zone_id}/workers/routes

**Resource:** [Worker Routes](../resources/Worker-Routes.md)
**List Routes**
**Operation ID:** `worker-routes-list-routes`

Returns routes for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Routes response. |
| 4XX | List Routes response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
