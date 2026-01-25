# GET /accounts/{account_id}/workers/observability/destinations

**Resource:** [Destinations](../resources/Destinations.md)
**Get Destinations**
**Operation ID:** `destination.list`

List your Workers Observability Telemetry Destinations

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | number | No |  |
| `perPage` | query | number | No |  |
| `order` | query | enum: asc, desc | No |  |
| `orderBy` | query | enum: created, updated | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful request |
| 401 | Unauthorized |
| 404 | Not found |
| 500 | Internal error |

