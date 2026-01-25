# PATCH /accounts/{account_id}/workers/observability/destinations/{slug}

**Resource:** [Destinations](../resources/Destinations.md)
**Update Destination**
**Operation ID:** `destination.update`

Update an existing Workers Observability Telemetry Destination

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `slug` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful request |
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not found |
| 500 | Internal error |

