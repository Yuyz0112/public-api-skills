# GET /status_dashboards/url_slugs/{url_slug}

**Resource:** [Status Dashboards](../resources/Status-Dashboards.md)
**Get a single Status Dashboard by `url_slug`**
**Operation ID:** `getStatusDashboardByUrlSlug`

Get a Status Dashboard by its PagerDuty `url_slug`.  A `url_slug` is a human-readable reference
for a custom Status Dashboard that may be created or changed in the UI. It will generally be a `dash-separated-string-like-this`.

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

