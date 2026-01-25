# GET /status_dashboards/url_slugs/{url_slug}/service_impacts

**Resource:** [Status Dashboards](../resources/Status-Dashboards.md)
**Get impacted Business Services for a  Status Dashboard by `url_slug`**
**Operation ID:** `getStatusDashboardServiceImpactsByUrlSlug`

Get Business Service Impacts for the Business Services on a Status Dashboard by its `url_slug`. A `url_slug` is a human-readable reference
for a custom Status Dashboard that may be created or changed in the UI. It will generally be a `dash-separated-string-like-this`.

This endpoint does not return an exhaustive list of Business Services but rather provides access to the most impacted on the Status Dashboard up to the limit of 200.

The returned Business Services are sorted first by Impact, secondarily by most recently impacted, and finally by name.

To get impact information about a specific Business Service on the Status Dashboard that does not appear in the Impact-sored response, use the `ids[]` parameter on the `/business_services/impacts` endpoint.

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

