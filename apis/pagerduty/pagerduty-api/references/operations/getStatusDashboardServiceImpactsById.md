# GET /status_dashboards/{id}/service_impacts

**Resource:** [Status Dashboards](../resources/Status-Dashboards.md)
**Get impacted Business Services for a Status Dashboard by `id`.**
**Operation ID:** `getStatusDashboardServiceImpactsById`

Get impacted Business Services for a Status Dashboard by `id`

This endpoint does not return an exhaustive list of Business Services but rather provides access to the most impacted on the specified Status Dashboard up to the limit of 200.

The returned Business Services are sorted first by Impact, secondarily by most recently impacted, and finally by name.

To get Impact information about a specific Business Service on the Status Dashboard that does not appear in the Impact-sorted response, use the `ids[]` parameter on the `/business_services/impacts` endpoint.

Scoped OAuth requires: `status_dashboards.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |
| 429 | (reference) |

