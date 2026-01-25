# DELETE /accounts/{account_id}/workers/observability/destinations/{slug}

**Resource:** [Destinations](../resources/Destinations.md)
**Delete Destination**
**Operation ID:** `destinations.delete`

Delete a Workers Observability Telemetry Destination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful request |
| 401 | Unauthorized |
| 404 | Not found |
| 500 | Internal error |

